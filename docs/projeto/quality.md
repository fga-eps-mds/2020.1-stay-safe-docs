# Gerenciamento de Qualidade do Produto

## 1. Introdução
Este documento enumera seis aspectos não funcionais do produto e como o grupo vai mensurá-los afim de garantir a qualidade do software construído.

## 2. Confiabilidade
De acordo com o ANSI "a confiabilidade de um produto de software é definida pelo funcionamento deste sem falhas por um tempo específico dentro de determinado ambiente", além disso espera-se de um software confiável a capacidade de se recuperar de erros o mais rápido possível. Mensurar a confiabilidade de um software é uma tarefa árdua pelo fato de ser um produto de alta complexidade em que cada desenvolvedor tem um conhecimento distinto da linguagem trabalhada e uma maneira subjetiva de pensar e escrever código. 

As ações e métricas que o time utiliza para garantir uma boa confiabilidade de software são:
* CI com suíte de testes (unitários, de usabilidade e integração / manuais ou automatizados) - Uma boa suíte de testes com alta cobertura consegue identificar diversas falhas antes desse código ir pra produção.
* CI com métricas de qualidade de código que analisem a lógica e a manutenibilidade do código - Um código manutenível e com lógica simples e direta é menos provável de apresentar falhas, visto que seu comportamento é mais previsível.
* Arquitetura de microsserviços - Cada um dos microsserviços pode ser re-erguido individualmente em caso de uma falha específica em um deles, melhorando a resiliência do software.
* Revisão de código - Através dela é possível identificar e exigir a correção de defeitos encontrados no código.
* Programação em pares - Identificação de possíveis problemas e práticas ruins de código pelo co-piloto impedindo que isso seja levado adiante.

## 3. Performance
A performance de um produto é determinada em como um sistema se comporta em termos de responsividade e estabilidade diante de uma certa carga. Três fatores muito influentes na performance são as tecnologias utilizadas, a qualidade do código feito e a arquitetura que comporta o sistema. Pode-se esperar diferentes níveis de performance para diferentes sistemas, um jogo precisa de tempo de resposta e latência muito inferiores a um site de e-commerce por exemplo, dessa forma as tecnologias escolhidas foram pensadas para entregar uma boa perfomance inserida no nosso contexto de aplicativo mobile.

As ações e métricas que o time utiliza para garantir uma boa performance do produto são:
* Teste de carga - Verificar o comportamento do sistema sobre determinada carga de usuários simulando seu uso real e averiguar que seu funcionamento continua normal.
* Verificar consumo de recursos - Identificar áreas (RAM, bateria, processador, rede) com alto consumo de recursos para propor possíveis intervenções.
* Arquitetura coesa - Evita problemas de perfomance em alto-nível, em uma arquitura ineficiente e complexa a informação percorre caminhos longos e demora para chegar em seu destino piorando a performance do software.
* Revisão de código - Através desta é possível identificar e exigir a correção de lógicas complexas onde elas não são necessárias.
* Programação em pares - Identificação de possíveis problemas e práticas ruins de código pelo co-piloto impedindo que isso seja levado adiante.
* Uso de framework que faz uso de funções nativas do celular - Melhor responsividade ao ter acesso fácil aos recursos disponibilizados pelo celular.

## 4. Privacidade e Segurança
No Brasil há uma legislação que regulamenta o tratamento de dados pessoas dos cidadãos, a [Lei Geral de Proteção de Dados Pessoais (LGPD)](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/Lei/L13709.htm).  A lei inclui o tratamento de dados em meio digital, então o serviço de usuário do Stay Safe usa alguns mecanismos com o objetivo de garantir a segurança e privacidade dos usuários e cumprimento da legislação:

* As senhas dos usuários são criptografadas antes de serem salvas no banco de dados;
* A autenticação dos usuários é feita com o uso de [JSON Web Tokens](https://jwt.io/);
* Os endpoints que realizam edição e deleção em dados de usuário estão protegidos de forma que apenas o próprio usuário poderá realizar a ação;
* As credenciais de acesso ao banco de dados em produção não serão expostas publicamente;
* Apenas o nome completo e o nome de usuário poderá ser vísivel por outros usuários;
* Não é possível ver quem cadastrou uma ocorrência, para manter o anonimato e privacidade do usuário;
* O aplicativo informará ao usuário como usa e armazena seus dados;

## 5. Manutenibilidade
Para uma manutenibilidade são usados padrões de códigos a partir de ferramentas de lint e qualidade de código, também é utilizado uma suite de testes para garantir o funcionamento das funcionalidades. Essas tecnologias são usadas na execução da pipeline, onde todo `push` feito no repositório é executado essa pipeline, assim com o Continuous Integration identificando possíveis problema no código. Após o código passar por essas etapas dentro de um Pull Request também é feito a revisão de código por integrantes, tendo assim um fator humano na revisão do código para garantir um código de qualidade sendo entregue. Além de todas essas verificações também foi pensado em uma arquitetura onde o projeto tenha uma boa manutenibilidade, separando bem os serviços utilizados pelo aplicativo e dividindo bem os seus papéis, escolhendo tecnologias adequadas ao propósito de cada serviço.

## 6. Usabilidade
Dentro do projeto será feito um teste de aceitação, onde será feito por pessoas que se encaixam nas personas definidas para o uso do aplicativo, podendo então fazer um testes com possíveis usuários final. No teste de aceitação será avaliado a partir das 10 heuristicas de Nielsen e das possíveis dores dos usuários, assim podendo avaliar todo o fluxo do aplicativo e o design como um todo.

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

