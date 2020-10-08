# Documento de Visão

## 1. Introdução

O documento de visão define o escopo de alto nível do produto, o propósito do software a ser desenvolvido e seu valor mercadológico. Este visa estabelecer e nivelar as expectativas dos envolvidos sobre o que exatamente é o software em questão.

### 1.1. Proposta

Este documento está organizado de acordo com a metodologia **RUP**, o *Rational Unified Process* e tem como objetivo estabelecer um posicionamento sobre a aplicação mobile **Stay Safe**, definindo detalhadamente as características da aplicação, apresentando uma visão clara dos desenvolvedores e objetivos. Para isso, serão apresentados tópicos referentes a descrição do problema a ser solucionado, posicionamento do produto em relação ao mercado, as partes interessadas e usuários e a definição do produto: funcionalidades e restrições.

### 1.2. Escopo

Este projeto tem como finalidade sistematizar e proporcionar melhor visibilidade de estatísticas relacionadas à incidência de crimes por região, de forma a facilitar a visualização pela sociedade, além de possibilitar o registro, alerta de ocorrências e avaliações de bairros.

### 1.3. Definições, Acrônimos e Abreviações

* **Stay Safe** - Nome do aplicativo mobile a ser desenvolvido
* **SSP** - Secretaria de Segurança Pública

## 2. Posicionamento

### 2.1. Oportunidade de Negócio

Com o histórico de já ter feito parte da lista dos [países mais perigosos do mundo](https://www.camara.leg.br/radio/programas/543467-brasil-e-um-dos-dez-paises-mais-violentos-do-mundo-revela-atlas-da-violencia-2018/), embora as estatísticas variem, o cenário brasileiro é sempre alarmante quando se trata de criminalidade e violência. Tendo isso em mente e com uso de dados abertos da secretaria de segurança pública, a aplicação foi pensada de modo que o usuário possa ter uma noção real da periculosidade de uma região e contribuir com a inserção de dados.

### 2.2. Instrução do Problema
**O problema de:** Não saber o nível de segurança de uma determinada região  
**Afeta:** Os cidadãos  
**Cujos impactos são:** O descuido ao transitar nessas regiões, facilitando a reincidência dos crimes mais comuns  
**Uma boa solução seria:** Uma aplicação que proporcione visibilidade de estatísticas relacionadas a segurança

### 2.3. Instrução de Posição do Produto

**Para:** Os cidadãos  
**Que:**  Desejam manter-se informados sobre os índices de segurança e contribuir com as estatísticas  
**O Stay Safe:**  É um aplicativo mobile  
**Que:** Permite que a população visualize dados da SSP ou fornecidos pelos usuários  
**Diferente de:** Aplicações similares que não permitem filtro de crimes e interação com os usuários   
**Nosso produto:** Oferece uma visualização em mapa com filtros e alertas sobre crimes ocorridos em locais próximos  

## 3. Descrições da Parte Interessada e do Usuário

Esta seção fornece um perfil das partes interessadas e usuários envolvidos no projeto. 

### 3.1. Perfis das Partes Interessadas

| Representantes | Descrição | Tipo | Responsabilidades | Critério de sucesso | Envolvimento |
|---- |---- |---- |---- |---- |---- |
| Brenda Santos, Daniel Primo, Hérick Portugues, Ítalo Alves, Lucas Boaventura, Luiz Pettengil, Tiago Samuel | Desenvolvimento de Software | Estudantes da Universidade de Brasília, cursando a disciplina de Métodos de Desenvolvimento de Software | Desenvolvimento, testes, documentação e implementação do software | Finalizar o desenvolvimento e realizar a entrega do software dentro dos prazos | Alto |
| Renan Schadt, Sara Silva, Rossicler Júnior | Gerenciamento de Projeto | Estudantes da disciplina de Engenharia de Produto de Software da Universidade de Brasília|Gerir e dar suporte à equipe de desenvolvimento, garantindo o melhor processo para o desenvolvimento do produto | Manter a equipe focada no projeto, manter o grupo ativo nos princípios ágeis, gerência dos riscos associados ao projeto e finalizar o desenvolvimento do projeto | Alto |
| Hilmer Neri | Docente | Professor das disciplinas Métodos de Desenvolvimento de Software e Engenharia de Produto de Software pela Universidade de Brasília |Avaliar e orientar os estudantes de ambas as disciplinas | Avaliar o produto em sua totalidade | Alto |

### 3.2. Ambiente do Usuário

A aplicação poderá ser acessada por meio de smartphones com sistema operacional Android, sendo necessário conexão com a internet para uso completo e atualizado do aplicativo.

### 3.3. Perfil do Usuário

| Representantes | Descrição | Tipo | Responsabilidades | Critério de sucesso | Envolvimento | 
|---- |---- |---- |---- |---- |---- |
| População | Público interessado em visualizar informações referentes à segurança | Usuário | Utilizar a aplicação | Visualizar os dados de maneira simples e eficiente | Médio |
| Vítima / Testemunha | Público interessado em denunciar um crime como vítima ou testemunha | Usuário | Contribuir com a inserção de dados na aplicação | Facilitar o processo de denúncia de um crime | Alto |

### 3.4. Principais Necessidades das Partes Interessadas ou do Usuário

| Necessidade | Prioridade | Interesse | Solução atual | Solução proposta | 
| ----|----|---- |---- |---- |
| Visualizar o grau de segurança de uma região | Alta | Visualizar índices de segurança com maior praticidade | Pesquisar manualmente os dados disponibilizados pela SSP e/ou noticiários | Aplicação que permite ao usuário uma visualização eficaz dos dados de segurança por meio de mapas e filtros |
| Auxiliar na denúncia de crimes | Alta | Guiar o usuário na denúncia de crimes | Pesquisar uma delegacia e fazer o boletim de ocorrência | Aplicação que indica e guia o usuário até a delegacia mais próxima, além de fornecer um atalho para realizar o boletim de ocorrência online | 
| Ser notificado sobre a segurança de um local | Média | Saber dos níveis de segurança do local | Pesquisar manualmente os dados em noticiários | Aplicação notifica o usuário sobre crimes em locais próximos ou perto de locais favoritados | 

## 4. Alternativas e Concorrência

Embora já existam propostas semelhantes, outras aplicações não obtiveram bons resultados e avaliações positivas do público, tanto por problemas técnicos quanto por não possuir tantas funcionalidades, como o cadastro de ocorrências pelos usuários, mapas de calor e filtragem de crimes.

Uma das soluções pesquisadas foi o [Monitor da Violência](https://g1.globo.com/monitor-da-violencia/) feito pelo portal de notícias G1 que fornece uma visão sistêmica dos índices de criminalidade em um determinado estado, seu foco é principalmente em mostrar a violência contra públicos específicos, o panorama de crimes violentos relacionados a facções criminosas e a comparação temporal relacionada a isso.

O [Instituto de Pesquisa Econômica Aplicada](https://www.ipea.gov.br/atlasviolencia/download/27/atlas-da-violencia-2020-principais-resultados) (IPEA) divulga um Atlas da Violência focando no panorama brasileiro como um todo e também em dados estaduais relacionados a crimes violentos ou contra minorias (mulheres, LGBT, entre outros).

A solução proposta **Stay Safe** foca em mostrar dados relacionados a segurança (seja ela relacionada a criminalidade ou não) a nível cidade/bairro/local, ao contrário das soluções pesquisadas que focam na análise dos dados dentro do panorama federal e estadual.

## 5. Definição do Produto

O **Stay Safe** trata-se de um aplicativo mobile para Android que busca contribuir para a segurança do usuário. A necessidade de monitorar a segurança de um local foi o que motivou os desenvolvedores deste projeto na criação do aplicativo. Além disso, existe uma preocupação em buscar informações sobre os diversos tipos de crime disponibilizados pelas SSP e informações relacionadas a segurança inseridas pelos usuários.

### 5.1. Perspectiva do Produto

O produto tem como principal característica ajudar a população informando sobre áreas de maior risco de acordo com as ocorrências relacionadas aquele local. Com diferenciais na visualização dos dados de segurança em mapas através de filtros e notificações sobre ocorrências inseridas por outros usuários.

### 5.2. Resumo dos Recursos

Dentre os principais recursos oferecidos pelo **Stay Safe** estão os serviços de cadastro, login e logout de usuário, visualização de dados de crimes obtidos pelas SSP e mostrados em forma de mapas gerados através de filtros, cadastro/visualização/edição de ocorrências por um usuário, redirecionamento para delegacias mais próximas ou para realização do boletim de ocorrência digital, ordenação de cidades por diferentes critérios e avaliação de bairros através de estrelas.

## 6. Funcionalidades do Produto

Os recursos e funcionalidades do **Stay Safe** compreendem funcionalidades a serem implementadas, buscando atender as necessidades identificadas dos usuários do aplicativo, para mais informações consulte o [Backlog do Produto](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/produto/visao/).

### 6.1. Cadastro, Login, Edição e Exclusão de Usuário - Épico Perfil

A aplicação possui um sistema para cadastro de usuários em conexão direta com o sistema de Login.

### 6.2. Visualização, Comparação e Ordenação de Cidades Através de Filtros de Crimes ou Mapas de Calor - Épico Cidade

A aplicação irá exibir os crimes por meio de mapas. A visualização dos mapas são facilitadas através das seguintes funcionalidades:

- Mapa de calor: Funciona a partir da quantidade de crimes per capita exibindo as áreas onde ocorreram mais crimes em vermelho e as áreas mais seguras em um tom verde. Os crimes exibidos no mapa podem ser filtrados através de categorias relacionadas ao tipo de crime.

### 6.3. Cadastro, Visualização, Edição e Exclusão de Avalições de Bairros - Épico Bairro

A aplicação possui um sistema de avaliação dos bairros, através de estrelas e características principais (positivas ou negativas).

### 6.4. Cadastro, Visualização, Edição e Exclusão de Ocorrências - Épico Local
Possibilidade de cadastro de ocorrências por um usuário relatando o tipo de crime, horário, local, entre outras informações. Sendo esta exibida no mapa para outros usuários.

### 6.5. Notificar Ocorrências em Locais Próximos ou Locais Favoritados - Épico Notificação
A aplicação possui um sistema de notificações sobre a segurança de um local favoritado pelo usuário e sobre atualizações nos dados das secretarias.

### 6.6. Direcionar Usuário a Delegacia Mais Próxima ou a um Boletim Eletrônico Digital - Épico Ajuda 
A aplicação pode redirecionar o usuário para uma delegacia mais próxima após o registro de uma ocorrência para a realização do Boletim de Ocorrência presencial, ou redirecionar para o Boletim Eletrônico, que pode ser realizado para crimes específicos.

## 7. Restrições
O aplicativo possui algumas restrições para uma melhor experiência do usuário, correto funcionamento do aplicativo e uso total das funcionalidades.

### 7.1. Restrições de Design

O aplicativo deve ter um design de alta compreensão e acessibilidade. Para mais informações consulte o tópico [Identidade Visual](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/produto/identidade/).

### 7.2. Restrições de Implementação

O aplicativo será implementado utilizando as linguagens Python, com o framework Flask, e Javascript, com o framework React Native. Para mais informações consulte o [Documento de Arquitetura](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/projeto/arquitetura/)

### 7.3. Restrições de Uso

Para instalação e usabilidade do aplicativo é necessário um smartphone com o sistema operacional Android com acesso à Play Store, conexão estável de internet para uso completo e atualizado do aplicativo e acesso a localização do usuário.

## 8. Critérios de Qualidade

Os critérios de qualidade do produto estão definidos em um documento próprio [Plano de Gerenciamento de Qualidade](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/projeto/quality/).

## 8. Referências

IBM Knowledge Center - Documento de Visão: A estrutura de tópicos do documento de visão. Disponível em: https://www.ibm.com/support/knowledgecenter/pt-br/SSWMEQ_3.0.1/com.ibm.rational.rrm.help.doc/topics/r_vision_doc.htm. Acesso em: 19 mar. 2020;

MIGUEL, Alexandre; ALVES, Dani; GUEDES, Gabriela; GOULART, Helena; ROBSON, João; MENEZES, Leticia; GUILHERME, Luiz; SCHADT, Renan; VINICIUS, Rômulo; HUGO, Victor. Projeto translate.me: Documento de Visão. Disponível em: https://translate-me.github.io/docs/documentos/projeto/doc_de_visao/. Acesso em: 19 mar. 2020;

MUNIZ, Amanda; RIOS, Calebe; LIMA, Eduardo; DUARTE, Indiara; RIBEIRO, Luciana; TAIRA, Luís; GOUVEIA, Micaella; BUTERS, Samuel; PATROCINIO, Sofia. Projeto Gaia: Documento de Visão. Disponível em: https://github.com/fga-eps-mds/2019.1-Gaia/blob/master/docs/produto/DocVisao.md. Acesso em: 20 mar. 2020;

## Histórico de Revisão

| Data | Versão| Descrição | Autor |
|----|----|----|----|
| 19/03/2020 | 0.1 | Adicionando Definição do Produto | Lucas e Tiago |
| 19/03/2020 | 0.2 | Adicionando Funcionalidades do Produto | Lucas e Tiago |
| 19/03/2020 | 0.3 | Adicionando Restrições | Lucas e Tiago |
| 20/03/2020 | 0.4 | Adicionando Restrições de Design, Segurança e Testes Unitários | Lucas e Tiago |
| 20/03/2020 | 0.5 | Adicionando Introdução | Brenda e Hérick |
| 20/03/2020 | 0.6 | Adicionando Planejamento | Brenda e Hérick |
| 21/03/2020 | 0.7 | Adicionando Descrições da Parte Interessada e Usuário | Brenda e Hérick |
| 22/03/2020 | 1.0 | Adicionando Usabilidade e Requisitos | Brenda, Hérick, Lucas e Tiago |
| 22/03/2020 | 1.1 | Revisando Documento | Brenda, Hérick, Lucas e Tiago |
| 24/08/2020 | 1.2 | Revisando Documento | Hérick |
| 07/10/2020 | 2.0 | Atualizando Documento com Alterações Feitas no Produto | Brenda, Lucas e Renan |
