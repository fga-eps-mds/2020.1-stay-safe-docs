# Qualidade do projeto

## 1. Introdução

## 2. Confiabilidade
* Testes 
* Capacidade de se recuperar de falhas
* Verificar comportamento do sistema quando muito demandado (teste de carga e/ou stress)

## 3. Performance
* Códigos otimizados
* Arquitetura 
* Capacidade do sistema (teste de carga e/ou stress)
* Consumo de recursos (bateria, memória, processamento e dados de internet)

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

## 6. Taxa de Entrega
* Continuous Deploy
* Métricas ágeis

## 7. Usabilidade
Dentro do projeto será feito um teste de aceitação, onde será feito por pessoas que se encaixam nas personas definidas para o uso do aplicativo, podendo então fazer um testes com possíveis usuários final. No teste de aceitação será avaliado a partir das 10 heuristicas de Nielsen e das possíveis dores dos usuários, assim podendo avaliar todo o fluxo do aplicativo e o design como um todo.

## 8. Acessibilidade
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

