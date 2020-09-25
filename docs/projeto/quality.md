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
* Ferramentas para lint, qualidade de código e suite de testes
* Revisão de PR
* CI
* Arquitetura 

## 6. Taxa de Entrega
* CD
* Métricas ágeis

## 7. Usabilidade
* Teste de aceitação
* Usar as 10 heuristicas de Nielsen

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

