# Backlog do Produto

## 1. Introdução
Este documento se destina a descrever e priorizar o conjunto de épicos e histórias que irão compor o escopo do aplicativo Stay Safe. Ao longo do projeto modificações podem ser feitas no backlog para que ele se adeque as novas expectativas sobre o produto.

## 2. Épicos
* Perfil
* Cidade
* Bairro
* Local Específico
* Notificação
* Ajuda

### 2.1 Diagrama de Gantt dos Épicos
O diagrama de Gantt ilustra o planejamento de ínicio e término de todo trabalho contido em um épico, a ordem de execução dos épicos é decidida por fatores como prioridade e dependência.

![Diagrama de Gantt dos Épicos](../images/backlog/Gantt.png "Diagrama de Gantt dos Épicos")

## 3. Histórias

### 3.1 Épico Perfil
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US01 | Me cadastrar na aplicação | Ter acesso a funcionalidade de registrar ocorrência | Must |
| US02 | Fazer o login na aplicação | Ter acesso a funcionalidade de registrar ocorrência | Must |
| US03 | Editar as minhas informações de cadastro | Corrigir uma informação errada | Should |
| US04 | Fazer o logout da aplicação | Entrar com outra conta | Must |
| US05 | Excluir minha conta | Me desvincular do aplicativo | Should |

### 3.2 Épico Cidade
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US06 | Visualizar estatísticas de crime de uma cidade | Ter uma real noção de sua segurança | Must |
| US07 | Comparar estatísticas de crime em anos diferentes numa mesma cidade | Verificar se a cidade está se tornando mais ou menos violenta | Could |
| US08 | Visualizar cidades ordenadas de acordo com critério escolhido | Visualizar qual a mais segura no critério que defini | Should |
| US09 | Visualizar cidades em formato de mapas de calor de acordo com o filtro escolhido | Comparar o nível de segurança das cidades ao meu redor | Must |


### 3.3 Épico Bairro
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US10 | Avaliar um bairro | Dar meu feedback sobre a segurança do bairro e ajudar outros usuários | Should |
| US11 | Editar avaliação de um bairro | Corrigir um feedback errado que registrei | Could |
| US12 | Excluir avaliação de um bairro | Apagar avaliação precipitada que realizei | Should |
| US13 | Visualizar avaliação de um bairro | Me informar sobre a segurança de um bairro | Should |
| US14 | Visualizar avaliação de bairros através de mapa de calor | Verificar os bairros mais seguros a minha volta | Could |
| US15 | Visualizar meu histórico de avaliação de bairros | Relembrar o que apontei nas minhas avaliações anteriores | Could |


### 3.4 Épico Local Específico
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US16 | Cadastrar anonimamente uma ocorrência | Contribuir com a segurança de outros usuários | Must |
| US17 | Editar as informações de uma ocorrência que registrei | Corrigir uma informação errada que foi inserida | Should |
| US18 | Excluir uma ocorrência que registrei | Apagar uma ocorrência que cadastrei indevidamente | Should |
| US19 | Navegar pelo mapa e verificar ocorrências registradas | Verificar o nível de segurança de um local | Must |
| US20 | Filtrar por tipos específicos de ocorrências | Verificar o nível de segurança de um local sob um aspecto específico | Should |
| US21 | Visualizar meu histórico de ocorrências registradas | Relembrar as ocorrências que registrei | Could |


### 3.5 Épico Notificação
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US22 | Favoritar locais |  | Should |
| US23 | Editar configurações de notificação | Escolher quais tipos de notificações desejo receber | Should |
| US24 | Ser notificado quando um crime ocorre próximo a um local favoritado | Me manter seguro nos locais que mais frequento | Should |
| US25 | Ser notificado quando um crime ocorre próximo ao meu local atual | Tomar medidas de precaução que aumentem minha segurança | Could |
| US26 | Ser notificado quando a aplicação é atualizada com novos dados das SSP | Visualizar os novos dados a respeito da minha cidade | Should |


### 3.6 Épico Ajuda
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US27 | Visualizar um guia ao entrar no aplicativo pela primeira vez | Identificar as principais funcionalidades do aplicativo | Could |
| US28 | Ser direcionado a delegacia mais próxima | Registrar um boletim de ocorrência a respeito do crime que sofri | Would |
| US29 | Ser encaminhado para fazer o cadastro de um boletim eletrônico | Registrar um boletim de ocorrência eletrônico a respeito do crime que sofri | Could |

## 4. Especificação das Histórias
Cada história descrita no tópico 3 é dividida em tasks e estas são criadas no repositório em que serão executadas. Assim é possível manter as histórias como uma forma amigável de entender o produto enquanto as tasks são usadas para criar tarefas pequenas, passíveis de serem feitas em uma sprint e que comunicam diretamente com os desenvolvedores. Neste tópico são mostradas as tasks que integram cada história presente no backlog.

Documentar toda dependência mínima entre as histórias do projeto não é viável devido ao caráter volátil do Backlog do Produto, as dependências entre histórias são revistas no contexto de uma sprint quando um planejamento é executado, afim de garantir que a equipe possui os recursos necessários para desenvolver a tarefa em questão.

É possível observar a prioridade das histórias de acordo com a sprint em que ela foi planejada, um exemplo é que a funcionalidade de **Cadastro de Usuário** é feita antes da **Edição de Usuário**, esse planejamento foi feito levando em consideração que a segunda história é dependente da primeira. 

### 4.1 Épico Perfil
A task abaixo está presente no fluxo de atividade de todas histórias do épico e precisa ser executada para que as histórias do Épico Perfil sejam concluídas.  
Task 1: [CRUD de Usuário - User - 8 pts - Sprint 2](https://github.com/fga-eps-mds/2020.1-stay-safe-docs/issues/29)  

**US01 - Me cadastrar na aplicação**   
Task 1: [Tela de Cadastro - Frontend - 8 pts - Sprint 3](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/1)  
Task 2: [Integração da Tela de Cadastro - Frontend - 3 pts - Sprint 4](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/5)

**US02 - Fazer o login na aplicação**   
Task 1: [Autenticação do Usuário - User - 5 pts - Sprint 3](https://github.com/fga-eps-mds/2020.1-stay-safe-user-service/issues/3)  
Task 2: [Tela de Login - Frontend - 3 pts - Sprint 4](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/2)

**US03 - Editar as minhas informações de cadastro**   
Task 1: [Telas para Visualização, Edição e Exclusão de Usuário - Frontend - 5 pts - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/11)   
Task 2: [Proibir Edição de Username - User - 1 pt - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-user-service/issues/15)

**US04 - Fazer o logout da aplicação**   
Task 1: [Tela para Logout de Usuário - Frontend - 3 pts - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/10)   

**US05 - Excluir minha conta**   
Task 1: [Telas para Visualização, Edição e Exclusão de Usuário - Frontend - 5 pts - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/11)  

### 4.2 Épico Cidade
As quatro tasks abaixo estão presentes no fluxo de atividade de todas histórias do épico e precisam ser executadas para que as histórias do Épico Cidade sejam concluídas.  
Task 1: [Extração SSP-DF - Secretary - 8 pts - Sprint 3](https://github.com/fga-eps-mds/2020.1-stay-safe-secretary-service/issues/1)  
Task 2: [Extração SSP-SP - Secretary - 8 pts - Sprint 4](https://github.com/fga-eps-mds/2020.1-stay-safe-secretary-service/issues/5)      
Task 3: [Endpoints para Obtenção de Dados - Secretary - 3 pts - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-secretary-service/issues/9)   
Task 4: Extração Dados Populacionais DF e SP - Secretary - X pts - Sprint 8   

**US06 - Visualizar estatísticas de crime de uma cidade**   
Task 1: Tela pra Visualizar Estatísticas - Frontend - X pts - Sprint 8   

**US07 - Comparar estatísticas de crime em anos diferentes numa mesma cidade**   
Task 1: Tela de Estatísticas Anuais - Frontend - X pts - Sprint 11   

**US08 - Visualizar cidades ordenadas de acordo com critério escolhido**   
Task 1: Tela de Cidades Ordenadas - Frontend - X pts - Sprint 9   

**US09 - Visualizar cidades em formato de mapas de calor de acordo com o filtro escolhido**   
Task 1: [Tela de Cidades Dispostas em Mapas de Calor - Frontend - 8 pts - Sprint 6](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/22) 

### 4.3 Épico Bairro
As três tasks abaixo estão presentes no fluxo de atividade de todas histórias do épico e precisam ser executadas para que as histórias do Épico Bairro sejam concluídas.  
Task 1: [CRUD de Avaliação - User - 5 pts - Sprint 4](https://github.com/fga-eps-mds/2020.1-stay-safe-user-service/issues/7)  
Task 2: [Endpoint para Avaliações - User - 2 pts - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-user-service/issues/14)  
Task 3: Lógica de Avaliações Médias - User - X pts - Sprint 8 

**US10 - Avaliar um bairro**  
Task 1: Tela de Avaliação - Frontend - X pts - Sprint 8 

**US11 - Editar avaliação de um bairro**  
Task 1: Tela para Visualização, Edição e Exclusão de Avaliação - Frontend - X pts - Sprint 10   

**US12 - Excluir avaliação de um bairro**  
Task 1: Tela para Visualização, Edição e Exclusão de Avaliação - Frontend - X pts - Sprint 10   

**US13 - Visualizar avaliação de um bairro**  
Task 1: Tela para Visualização Completa de Avaliação - Frontend - X pts - Sprint 10   

**US14 - Visualizar avaliação de bairros através de mapa de calor**  
Task 1: Tela de Bairros Dispostos em Mapas de Calor - Frontend - X pts - Sprint 9    

**US15 - Visualizar meu histórico de avaliação de bairros**   
Task 1: Tela de Histórico de Avaliações - Frontend - X pts - Sprint 10   

### 4.4 Épico Local Específico
As três tasks abaixo estão presentes no fluxo de atividade de todas histórias do épico e precisam ser executadas para que as histórias do Épico Local Específico sejam concluídas.   
Task 1: [CRUD de Ocorrência - User - 5 pts - Sprint 3](https://github.com/fga-eps-mds/2020.1-stay-safe-user-service/issues/2)  
Task 2: [Integração com API do Maps - Frontend - 5 pts - Sprint 4](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/3)  
Task 3: [Endpoint para Ocorrências - User - 2 pts - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-user-service/issues/14)    

**US16 - Cadastrar anonimamente uma ocorrência**  
Task 1: [Tela de Cadastro de Ocorrência - Frontend - 5 pts - Sprint 5](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/9)  
Task 2: [Associar Ocorrência a Localização - Frontend - 5 pts - Sprint 6](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/21) 

**US17 - Editar as informações de uma ocorrência que registrei**  
Task 1: [Tela para Visualização, Edição e Exclusão de Ocorrências - Frontend - 5 pts - Sprint 6](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/23)  

**US18 - Excluir uma ocorrência que registrei**  
Task 1: [Tela para Visualização, Edição e Exclusão de Ocorrências - Frontend - 5 pts - Sprint 6](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/23)  

**US19 - Navegar pelo mapa e verificar ocorrências registradas**  
Task 1: [Tela de Detalhes da Ocorrência - Frontend - 3 pts - Sprint 7](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/33) 

**US20 - Filtrar por tipos específicos de ocorrências**   
Task 1: Tela de Filtros de Ocorrência - Frontend - X pts - Sprint 9

**US21 - Visualizar meu histórico de ocorrências registradas**  
Task 1: [Tela para Visualização, Edição e Exclusão de Ocorrências - Frontend - 5 pts - Sprint 6](https://github.com/fga-eps-mds/2020.1-stay-safe-front-end/issues/23)   


### 4.5 Épico Notificação  
**US22 - Favoritar locais**  
Task 1: CRUD Locais Favoritos - Frontend - X pts - Sprint 11    
Task 2: Tela Favoritar Locais - Frontend - X pts - Sprint 11    

**US23 - Editar configurações de notificação**  
Task 1: Configurar Sistema de Notificações - Frontend - X pts - Sprint 12   
Task 2: Controle de Notificações pelo Usuário - Frontend - X pts - Sprint 13   

**US24 - Ser notificado quando um crime ocorre próximo a um local favoritado**   
Task 1: Configurar Sistema de Notificações - Frontend - X pts - Sprint 13   
Task 2: Notificar Ocorrências Próximas a Local Favoritado - Frontend - X pts - Sprint 13    

**US25 - Ser notificado quando um crime ocorre próximo ao meu local atual**  
Task 1: Configurar Sistema de Notificações - Frontend - X pts - Sprint 12  
Task 2: Obter Usuários Próximos a Ocorrências Cadastradas - Frontend - X pts - Sprint 14  
Task 3: Notificar Ocorrências Próximas a Local Atual - Frontend - X pts - Sprint 15    

**US26 - Ser notificado quando a aplicação é atualizada com novos dados das SSP**  
Task 1: Configurar Sistema de Notificações - Frontend - X pts - Sprint 12   
Task 2: Notificar Novos Dados das SSP - Frontend - X pts - Sprint 13   

### 4.6 Épico Ajuda
**US27 - Visualizar um guia ao entrar no aplicativo pela primeira vez**  
Task 1: Elaborar Guia do Aplicativo - Frontend - X pts - Sprint 12 

**US28 - Ser direcionado a delegacia mais próxima**  
Task 1: Recomendações de Delegacias Próximas ao Usuário - Frontend - X pts - Sprint 15    

**US29 - Ser encaminhado para fazer o cadastro de um boletim eletrônico**  
Task 1: Sugestão de Registro de Boletim Eletrônico - Frontend - X pts - Sprint 14  
