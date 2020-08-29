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

## 3. Histórias

### 3.1 Épico Perfil
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US01 | Me cadastrar na aplicação | Ter acesso a funcionalidade de registrar ocorrência | Must |
| US02 | Fazer o login na aplicação | Ter acesso a funcionalidade de registrar ocorrência | Must |
| US03  | Editar as minhas informações de cadastro | Corrigir uma informação errada | Should |
| US04 | Fazer o logout da aplicação | Entrar com outra conta | Must |
| US05 | Excluir minha conta | Me desvincular do aplicativo | Should |

### 3.2 Épico Cidade
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US06 | Visualizar estatísticas de crime de uma cidade | Ter uma real noção de sua segurança | Must |
| US07 | Comparar estatísticas de crime em anos diferentes numa mesma cidade | Verificar se a cidade está se tornando mais ou menos violenta | Could |
| US08 | Visualizar cidades ordenadas de acordo com critério escolhido | Visualizar qual a mais segura no criterio que defini | Should |
| US09 | Visualizar cidades em formato de mapas de calor de acordo com o filtro escolhido | Comparar o nível de segurança das cidades ao meu redor | Must |

----

| ID | Eu, como desenvolvedor gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| TS01 | Obter os dados populacionais dos estados de SP e DF | Utilizar esses dados para calcular quantidade de crimes per capita | Should |
| TS02 | Extrair e tratar os dados de crimes da SSP-SP | Mostrar as estatísticas de crimes aos usuários | Must |
| TS03 | Extrair e tratar os dados de crimes da SSP-DF | Mostrar as estatísticas de crimes aos usuários | Must |


### 3.3 Épico Bairro
| ID | Eu, como usuário gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| US10 | Avaliar um bairro | Dar meu feedback sobre a segurança do bairro e ajudar outros usuários | Should |
| US11 | Editar avaliação de um bairro | Corrigir um feedback errado que registrei | Could |
| US12 | Excluir avaliação de um bairro | Apagar avaliação precipitada que realizei | Should |
| US13 | Visualizar avaliação de um bairro | Me informar sobre a segurança de um bairro | Should |
| US14 | Visualizar avaliação de bairros através de mapa de calor | Verificar os bairros mais seguros a minha volta | Could |
| US15 | Visualizar meu histórico de avaliação de bairros | Relembrar o que apontei nas minhas avaliações anteriores | Could |

----

| ID | Eu, como desenvolvedor gostaria de... | Para poder... | Priorização |
|---|---|---|---|
| TS04 | Identificar bairros de uma cidade | Indicar os alvos de avaliação dos usuários | Should |

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