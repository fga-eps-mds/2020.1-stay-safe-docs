# Gerenciamento de Qualidade do Produto

## 1. Introdução
Este documento enumera seis aspectos não funcionais do produto e como o grupo vai mensurá-los afim de garantir a qualidade do software construído.

## 2. Confiabilidade
De acordo com o ANSI (American National Standards Institute) "a confiabilidade de um produto de software é definida pelo funcionamento deste sem falhas por um tempo específico dentro de determinado ambiente", além disso espera-se de um software confiável a capacidade de se recuperar de erros o mais rápido possível. Mensurar a confiabilidade de um software é uma tarefa árdua pelo fato de ser um produto de alta complexidade em que cada desenvolvedor tem um conhecimento distinto da linguagem trabalhada e uma maneira subjetiva de pensar e escrever código. 

As ações e práticas que o time utiliza ou pretende utilizar para garantir uma boa confiabilidade de software são: 

* CI com suíte de testes (unitários e de integração) - Uma boa suíte de testes com alta cobertura consegue identificar diversas falhas antes desse código ir pra produção.  No backend o time pretende atingir 90% de cobertura de testes unitários.
* Qualidade de código - Um código manutenível e com lógica simples e direta é menos provável de apresentar falhas, visto que seu comportamento é mais previsível. Portanto, o time está utilizando a ferramenta [Code Climate](https://codeclimate.com/) para monitorar a qualidade do código. A ferramenta dá notas para o código. A equipe pretende ter no mínimo nota B em todos os repositório de código.
* Arquitetura de microsserviços - O backend do aplicativo usa arquitetura de microsserviços, então em caso de falha de um dos serviços, o outro pode continuar funcionando normalmente e o que falhou pode ser re-erguido individualmente.
* Revisão de código - Com essa prática é possível identificar e exigir a correção de defeitos encontrados no código ou no comportamento de alguma funcionalidade.  
* Ambientes de Produção de Homologação - Os serviços de backend sempre serão testados em um ambiente de homologação antes de serem disponibilizados para uso em produção. Isso garante que a versão disponibilizada pra uso é a que terá menos falhas possíveis.

## 3. Performance
A performance de um produto é determinada em como um sistema se comporta em termos de responsividade e estabilidade diante de uma certa carga. Três fatores muito influentes na performance são as tecnologias utilizadas, a qualidade do código feito e a arquitetura que comporta o sistema. Pode-se esperar diferentes níveis de performance para diferentes sistemas, um jogo precisa de tempo de resposta e latência muito inferiores a um site de e-commerce por exemplo, dessa forma as tecnologias escolhidas foram pensadas para entregar uma boa perfomance inserida no nosso contexto de aplicativo mobile.

As ações e práticas que o time utiliza ou pretende utilizar para garantir uma boa confiabilidade de software são: 

* Teste de carga - Verificar o comportamento do sistema sobre determinada carga de usuários simulando seu uso real e averiguar se seu funcionamento continua normal.
* Verificar consumo de recursos - Identificar áreas (RAM, bateria, processador, rede) com alto consumo de recursos para propor possíveis intervenções.
* Arquitetura coesa - O sistema usa uma arquitura em que o fluxo de dados é simples e eficiente. Em uma arquitura ineficiente e complexa a informação percorre caminhos longos e demora para chegar em seu destino piorando a performance do software.
* Verificar complexidade assintótica - Monitorando a complexidade do código a performance pode ser melhorada no uso de recursos e no tempo gasto.
* Funções nativas do celular - O frontend é feito com um framework que faz uso de funções nativas do celular, isso melhora a responsividade ao ter acesso fácil aos recursos disponibilizados pelo celular.

## 4. Privacidade e Segurança
No Brasil há uma legislação que regulamenta o tratamento de dados pessoais dos cidadãos, a [Lei Geral de Proteção de Dados Pessoais (LGPD)](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/Lei/L13709.htm).  A lei inclui o tratamento de dados em meio digital, então o serviço de usuário do Stay Safe usa alguns mecanismos com o objetivo de garantir a segurança e privacidade dos usuários e cumprimento da legislação:

* As senhas dos usuários são criptografadas antes de serem salvas no banco de dados;
* A autenticação dos usuários é feita com o uso de [JSON Web Tokens](https://jwt.io/);
* Os endpoints que realizam edição e deleção em dados de usuário estão protegidos de forma que apenas o próprio usuário poderá realizar a ação;
* As credenciais de acesso ao banco de dados em produção não serão expostas publicamente;
* Apenas o nome completo e o nome de usuário poderá ser vísivel por outros usuários;
* Não é possível ver quem cadastrou uma ocorrência, para manter o anonimato e privacidade do usuário;
* O aplicativo informará ao usuário como usa e armazena seus dados;

## 5. Manutenibilidade
Manutenibilidade é o quão o fácil o sistema pode ser modificado ou evoluído.

Para garantir manutenibilidade no Stay Safe são usados padrões de códigos de ferramentas de `lint` que são programas de checagem de código estático que procuram erros programáticos ou de estilo. Também é utilizado uma suite de testes para garantir o correto comportamento das funcionalidades. 
Essas verificações são feitas na execução da [pipeline de Continuos Integration](../projeto/gcs.md), em que todo `push` feito noa repositórioa é executado essa pipeline.
Há também o uso do Code Climate que analisa e fornece métricas sobre aspectos do código como complexidade, repetição, etc.

Após o código passar por essas etapas dentro de um Pull Request também é feita a revisão por integrantes da equipe, tendo assim um fator humano na revisão do código para garantir a qualidade do que está sendo entregue.

Além de todas essas verificações também foi pensado em uma arquitetura simples para manutenibilidade, separando bem os serviços utilizados pelo aplicativo e dividindo bem os seus papéis, escolhendo tecnologias adequadas ao propósito de cada serviço.

## 6. Usabilidade
Usabilidade é a facilidade com que os usuários lidam com a aplicação.
Para avaliar a usabilidade do Stay Safe, a equipe fará testes de aceitação com pessoas que não fizeram parte do desenvolvimento e que se encaixam no perfil das [personas](../produto/product-definition.md) definidas como usuárias do aplicativo, podendo então fazer testes com possíveis usuários final.

Para avaliar o fluxo de ações do aplicativo e o design como um todo, nos testes de aceitação serão observadas as dores dos usuários e serão orientados e avaliados a partir das 10 heuristicas de Nielsen que aborda, entre outros, aspectos como:

* Visibilidade de Status do Sistema
* Relação entre interface e o mundo real
* Liberdade e controle do usuário
* Consistência
* Estética e design minimalista
* Flexibilidade e eficiência de uso

## 7. Acessibilidade
Os padrões de acessibilidade compreendem um conjunto de recomendações destinadas a  criadores de conteúdo Web. O objetivo é apresentar o mesmo conteúdo a todas as pessoas sem nenhum obstáculo para navegabilidade do usuário, independente de sua condições físicas e/ou motoras.  

Os padrões da internet são regulamentados pelo World Wide Web Consortium (W3C), principal organização de padronização da World Wide Web (WWW). A organização lançou a cartilha de [Recomendações de Acessibilidade para Conteúdo Web (W3CAG)](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/) que tem como missão promover a acessibilidade na internet para pessoas com deficiência, nela há diversas instruções sobre como formatar e orientar a programação de sistemas digitais.  

Para avaliar a acessibilidade do aplicativo Stay Safe, a equipe realizará testes de aceitação com usuários portadores de necessidades especiais. O teste terá como base a cartilha da W3C e avaliará pontos como:  

* Cores e contraste;  
* Distância entre ícones;  
* Área em volta dos elementos touch/clicáveis;  
* Alternativas aos elementos sonoros;  
* Sugestões visuais que garatam a informação;  
* Textos descritivos em formulários;  
* Clareza nos links mostrados;  

## 8. Referências
* [Guia Prático](https://www.sealights.io/software-quality/measuring-software-quality-a-practical-guide/)
* [Recomendações de Acessibilidade para Conteúdo Web (W3CAG)](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/)
* [Heurísticas de Nielsen](https://www.nngroup.com/articles/ten-usability-heuristics/)
* [Lei Geral de Proteção de Dados Pessoais (LGPD)](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/Lei/L13709.htm)
* [Artigo Confiabilidade de Software](https://users.ece.cmu.edu/~koopman/des_s99/sw_reliability/)

