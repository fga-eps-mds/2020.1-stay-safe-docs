# StaySafe - Documento de Visão

## 1. Introdução

O documento de visão define o escopo de alto nível do produto, o propósito do software a ser desenvolvido e seu valor mercadológico. Este visa estabelecer e nivelar as expectativas dos envolvidos sobre o que exatamente é o software em questão.

### 1.1 Proposta

Este documento tem como objetivo estabelecer um posicionamento sobre a aplicação mobile **Stay Safe**, trazendo as características, utilidades e o processo de desenvolvimento como um todo. Visa promover o entendimento fácil do leitor, seja ele usuário ou desenvolvedor, expondo suas funcionalidades e definindo os principais requisitos.

### 1.2 Escopo

Este projeto tem como finalidade sistematizar e proporcionar melhor visibilidade de estatísticas relacionadas à incidência de crimes por região, de forma a facilitar a visualização pela sociedade, além de possibilitar o registro e alerta de ocorrências.

### 1.3 Definições, Acrônimos e Abreviações

* **UnB** - Universidade de Brasília
* **FGA** - Faculdade do Gama (UnB)
* **MDS** - Métodos de Desenvolvimento de Software
* **EPS** - Engenharia de Produto de Software
* **Stay Safe** - Nome do aplicativo a ser desenvolvido
* **SSP** - Secretaria de Segurança Pública

### 1.4 Referências

IBM Knowledge Center - Documento de Visão: A estrutura de tópicos do documento de visão. Disponível em: https://www.ibm.com/support/knowledgecenter/pt-br/SSWMEQ_3.0.1/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.htm. Acesso em: 19 mar. 2020;

MIGUEL, Alexandre; ALVES, Dani; GUEDES, Gabriela; GOULART, Helena; ROBSON, João; MENEZES, Leticia; GUILHERME, Luiz; SCHADT, Renan; VINICIUS, Rômulo; HUGO, Victor. Projeto translate.me: Documento de Visão. Disponível em: https://translate-me.github.io/docs/documentos/projeto/doc_de_visao/. Acesso em: 19 mar. 2020;

MUNIZ, Amanda; RIOS, Calebe; LIMA, Eduardo; DUARTE, Indiara; RIBEIRO, Luciana; TAIRA, Luís; GOUVEIA, Micaella; BUTERS, Samuel; PATROCINIO, Sofia. Projeto Gaia: Documento de Visão. Disponível em: https://github.com/fga-eps-mds/2019.1-Gaia/blob/master/docs/produto/DocVisao.md. Acesso em: 20 mar. 2020;

### 1.5 Visão Geral

Este documento visa descrever detalhadamente as características da aplicação, apresentando uma visão clara dos desenvolvedores e objetivos. Para isso, serão apresentados tópicos referentes a descrição do problema a ser solucionado, posicionamento do produto em relação ao mercado, as partes interessadas e usuários, a definição do produto: funcionalidades e restrições, e requisitos para a aplicação do produto.

## 2. Posicionamento

### 2.1 Oportunidade de Negócio

Com o histórico de já ter feito parte da lista dos países mais perigosos do mundo, embora as estatísticas variem, o cenário brasileiro é sempre alarmante quando se trata de criminalidade e violência. Tendo isso em mente e com uso de dados abertos da secretaria de segurança pública, a aplicação foi pensada de modo que o usuário possa ter uma noção real da perículosidade de uma região e contribuir com a inserção de dados, caso se torne vítima ou testemunha.

### 2.2 Instrução do Problema

| O problema de |Não saber o grau de criminalidade em determinada região |
|----|----|
| Afeta | Os cidadãos |
| Cujos impactos são | O descuido ao transitar nessas regiões, facilitando a reincidência dos crimes mais comuns |
| Uma boa solução seria | Uma aplicação que informasse os índices de criminalidade de cada região |

### 2.3 Instrução de Posição do Produto

| Para | Os cidadãos |
|----|----|
| Que | Desejam manter-se informados sobre os índices de criminalidade e contribuir com as estatísticas |
| O Stay Safe | É um aplicativo mobile |
| Que | permite que a população visualize dados da segurança pública e fornecidos pelos usuários e registre novas ocorrências |
| Diferente de | Aplicações similares que não permitem filtro de crimes e interação com os usuários |
| Nosso produto | Oferece uma visualização em mapa com filtros e alertas sobre crimes ocorridos com usuários próximos |

## 3. Descrições da Parte Interessada e do Usuário

Esta seção fornece um perfil das partes interessadas e usuários envolvidos no projeto. 

### 3.1 Resumo da parte interessada

| Nome | Descrição | Responsabilidade | 
|----|----|----|
|Equipe de Desenvolvimento| Graduandos em Engenharia de Software, cursando a disciplina Métodos de desenvolvimento de Software, pela Universidade de Brasília | Desenvolvimento, testes, documentação e implementação do software |
| Equipe de Gestão de Processo | Graduandos em Engenharia de Software, cursando a disciplina Engenharia de Produto de Software, pela Universidade de Brasília | Gerir e dar suporte à equipe de desenvolvimento, garantindo o melhor processo para o desenvolvimento do produto |
|Equipe docente| Professor da Universidade de Brasília do curso de Engenharia de Software | Avaliar e orientar os estudantes de ambas as disciplinas |

### 3.2 Resumo do usuário

| Nome | Descrição | Responsabilidade |
|----|----|----|
| População | Público interessado em visualizar informações referentes à criminalidade | Utilizar a aplicação | 
| Vítima / testemunha | Público interessado em denunciar um crime como vítima ou testemunha | Contribuir com a inserção de dados na aplicação |

### 3.3 Ambiente do Usuário

A aplicação poderá ser acessada por meio de smartphones com sistema operacional Android, sendo necessário conexão com a internet para uso completo e atualizado do aplicativo.

### 3.4 Perfis das partes interessadas

|Representantes |Descrição |Tipo |Responsabilidades |Critério de sucesso |Envolvimento |Problemas/comentários| 
|---- |---- |---- |---- |---- |---- |----| 
| Brenda Santos, Daniel Primo, Herick Portugues, Italo Alves, Lucas Boaventura, Luiz Pettengil, Tiago Samuel | Desenvolvimento de Software | Estudantes da Universidade de Brasília, cursando a disciplina de Métodos de Desenvolvimento de Software | Desenvolvimento, testes, documentação e implementação do software | Finalizar o desenvolvimento e realizar a entrega do software dentro dos prazos | Alto | - | 
| Renan Schadt , Sara Silva, Rossicler Júnior | Gerenciamento de Projeto | Estudantes da disciplina de Engenharia de Produto de Software da Universidade de Brasília|Gerir e dar suporte à equipe de desenvolvimento, garantindo o melhor processo para o desenvolvimento do produto | Manter a equipe focada no projeto, manter o grupo ativo nos princípios ágeis, gerência dos riscos associados ao projeto e finalizar o desenvolvimento do projeto | Alto | - |
| Hilmer Neri | Docente |Professor das disciplinas Métodos de Desenvolvimento de Software e Engenharia de Produto de Software pela Universidade de Brasília |Avaliar e orientar os estudantes de ambas as disciplinas | Avaliar o produto em sua totalidade | Alto | - |

### 3.5 Perfil do usuário

|Representantes |Descrição |Tipo |Responsabilidades |Critério de sucesso |Envolvimento| 
|---- |---- |---- |---- |---- |---- |
| População | Público interessado em visualizar informações referentes à criminalidade | Usuário | Utilizar a aplicação | Visualizar os dados de maneira simples e eficiente | Médio |
| Vítima / Testemunha | Público interessado em denunciar um crime como vítima ou testemunha | Usuário | Contribuir com a inserção de dados na aplicação | Facilitar o processo de denúncia de um crime | Alto |

### 3.6 Principais necessidades das partes interessadas ou do usuário

| Necessidade|Prioridade |Interesse |Solução atual |Solução proposta | 
| ----|----|---- |---- |---- |
| Visualizar o grau de criminalidade de uma região | Alta | Visualizar índices de criminalidade com maior praticidade | Pesquisar manualmente os dados disponibilizados pela SSP e/ou noticiários | Aplicação que permite ao usuário uma visualização eficaz dos dados de criminalidade por meio de mapas |
| Auxiliar na denúncia de crimes | Alta | Guiar o usuário na denúncia de crimes | Pesquisar uma delegacia e fazer o boletim de ocorrência | Aplicação que indica e guia o usuário até a delegacia mais próxima, além de fornecer um atalho para realizar o boletim de ocorrência online | 

### 3.7 Alternativas e concorrência

Embora já existam propostas semelhantes, outras aplicações não obtiveram bons resultados e avaliações positivas do público, tanto por problemas técnicos quanto por não possuir tantas funcionalidades, como o cadastro de ocorrências pelos usuários, mapas de calor e filtragem de crimes.

## 4. Definição do Produto

O **Stay Safe** trata-se de um aplicativo mobile para Android que busca contribuir para a segurança do usuário. A necessidade de vizualização de informações sobre crimes foi o que motivou os desenvolvedores deste projeto na criação do aplicativo. Além disso, existe uma preocupação em buscar informações sobre os diversos tipos de crime estabelecidos por lei. As informações sobre os crimes foram obtidas através da Secretaria de Estado de Segurança Pública e experiências de usuários.

### 4.1. Perspectiva do Produto

O Produto tem como principal característica ajudar as pessoas informando sobre áreas de maior risco de acordo com a categorização do crime. Com diferenciais na vizualização dos dados criminais em mapas através de filtros e notificações sobre crimes ocorridos com outros usuários.

### 4.2. Resumo dos Recursos

Dentre os principais recursos oferecidos pelo **Stay Safe** estão os serviços de cadastro, login e logout de usuário, vizualização de dados de crimes e delegacias através dos mapas e seus filtros, cadastro/vizualização/edição de ocorrências por um usuário, redirecionamento para delegacias mais próximas ou para realização do boletim de ocorrência digital, ordenação de cidades por critérios diferentes.

## 5. Funcionalidades do Produto

Os recursos e funcionalidades do aplicativo mobile **Stay Safe**  compreendem serviços implementados, buscando atender as necessidades identificadas dos usuários do aplicativo, aqui descritas em ordem prioridade.

### 5.1. Login e Cadastro

A aplicação possui um sistema para cadastro de usuários em conexão direta com o sistema de Login, fazendo uso tanto de um método nativo para o fluxo de registro, quanto métodos que integrem informações de outras aplicações (como Facebook ou Google), permitindo acesso facilitado ao usuário.

### 5.2. Vizualização de mapas

A aplicação irá exibir os crimes por meio de mapas. A vizualização dos mapas são facilitadas através das seguintes funcionalidades:

#### 5.2.1. Mapas de Calor

Este mapa funciona a partir da quantidade de crimes, por área e por Delegacia de Polícia. Exibindo as áreas onde ocorreram mais crimes em vermelho e as áreas mais seguras em um tom mais azulado.

#### 5.2.2. Filtros

Os crimes exibidos no mapa podem ser filtrados através de categorias como:
informações obtidas com a SSP ou com os usuários, tipo de crime, locais do crime, crimes contra um grupo específico de pessoas.

#### 5.2.3. Delegacias

Os mapas exibidos também mostrarão as delegacias que estão dentro do campo de visão do usuário no mapa. Mostrando também informações sobre a delegacia e o seu campo de atuação.

### 5.3. Cadastro de ocorrências por um usuário

Possibilidade de cadastro de ocorrências por um usuário relatando o tipo de crime, horário e local. Sendo esse exibido no mapa para outros usuários.

#### 5.3.1. Redirecionamento após cadastro de ocorrência

O aplicativo pode redirecionar o usuário para uma delegacia mais próxima após o registro de uma ocorrência para a realização do B.O. ou redirecionar para o B.O. Eletrônico, que pode ser realizado online para crimes específicos.

### 5.4. Ordenação de cidades por critérios diferentes

As cidades podem ser ordenadas através de filtros escolhidos pelo usuário, como categorias de crimes ou mais Delegacias de Polícias em uma determinada de região.

## 6. Restrições

### 6.1. Restrições de Design

O aplicativo deve ter um design de alta compreensão e acessibilidade.

### 6.2. Restrições de Implementação

O aplicativo será implementado utilizando as linguagens Python, com o framework Flask, e Javascript, com o framework React Native. 

### 6.3. Restrições de Uso

Para instalação e usabilidade do aplicativo é necessário um smartphone com o sistema operacional Android com acesso à Play Store. Além de acesso a conexão estável de internet para uso completo e atualizado do aplicativo.

## 7. Critérios de Qualidade

### 7.1. Testes unitários

Serão utilizados testes unitários em cada serviço criado no back-end para garantir a alta qualidade do codigo.

### 7.2. Usabilidade

...

## 8. Requisitos

...

## 9. Documentação Adicional

...
