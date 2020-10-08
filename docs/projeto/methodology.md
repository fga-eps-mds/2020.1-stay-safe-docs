# Definição de Metodologia 

## 1. Introdução
Este documento tem por finalidade definir a metodologia a ser utilizada no projeto, descrevendo as metodologias usadas como base e mostrando os artefatos e rotinas selecionados destas.

## 2. Metodologias de Base
### 2.1 Scrum
O Scrum é uma metodologia ágil que contém diversas rotinas para manter a equipe engajada e atualizada sobre o projeto, a se organizarem enquanto resolvem um problema e a refletirem sobre os êxitos e fracassos para melhorarem continuamente. Scrum é um framework estrutural usado para gerenciar o desenvolvimento de produtos. Ele é fundado nos princípios de transparência, inspeção e adaptação. Aos princípios do Scrum integramos eventos, papéis e artefatos, administrando as relações e interações entre eles.

Os papéis do Scrum são Product Owner, Architect, Scrum Master e time de desenvolvimento. O Product Owner é o responsável por maximizar o valor do produto e gerenciar o Product Backlog, garantindo que ele está claro para toda equipe. O Architect é responsável por elaborar a arquitetura do software e garantir que ela seja seguida. O Scrum Master tem a função de garantir que a equipe está cumprindo as regras da metodologia. O time de desenvolvimento, tem a função de incrementar o produto a cada sprint.

Os eventos do Scrum são: Sprint (período de um mês ou menos onde a equipe se dedica a incrementar o produto), Planejamento de Sprint (reunião ao início de cada sprint onde a equipe decide o que será feito nesta), Review e Retrospectiva da Sprint (a equipe analisa como foi a sprint e quais atividades atividades e artefatos alocados a ela foram finalizados) e Daily (reunião diária para alinhamento da equipe sobre o andamento da sprint).

Os artefatos do Scrum são: Product Backlog (lista ordenada de tudo que é necessário no produto), Sprint Backlog (conjunto de itens do backlog do produto selecionados para a sprint) e Incremento (soma de todos os itens do backlog do produto completados durante uma sprint).

![](https://i2.wp.com/www.scrumportugal.pt/wp-content/uploads/como-funciona-o-scrum.png?fit=1300%2C570)

### 2.2 Kanban
O Kanban, trata-se de uma simbologia visual usada no desenvolvimento de produtos para registrar o progresso das atividades. Essa metodologia foi criada pela empresa Toyota e integra o famoso sistema Toyota de produção.

O Kanban é orientado através de colunas, em que cada uma representa diferentes estados de completeza de uma atividade (a fazer, fazendo, feito), as atividades (cartões visuais) vão transitando entre as colunas, mostrando o andamento do projeto.

![](https://blog.caelum.com.br/wp-content/uploads/2016/01/kanban.jpg)

### 2.3 XP
XP é a sigla de uma metodologia ágil de desenvolvimento designada Extreme Programming, com foco em produzir softwares de qualidade e fornecer qualidade de vida aos desenvolvedores. Os cinco valores básicos do XP são:

1. Comunicação: Fundamental para transferir conhecimento entre o time, o framework apoia a comunicação cara a cara, com o apoio de quadro branco e outros mecanismos de desenho.

2. Simplicidade: Evitar desperdícios e só fazer o que é necessário e útil, de maneira a facilitar o entendimento e a manutenção do produto.

3. Feedback Constante: Através do feedback constante é possível identificar pontos a melhorar no software e produzir melhorias e evoluções rapidamente, assim que uma fragilidade é detectada, ajustando os próximos passos do desenvolvimento.

4. Coragem: Coragem para tomar decisões mal-vistas no presente, que irão trazer bom retorno no futuro, como levantar problemas organizacionais que reduzem a produtividade do time, aceitar e reagir a um feedback negativo, parar de fazer algo que não está funcionando e tentar algo diferente.

5. Respeito: É necessário respeito entre os membros da equipe para que haja boa comunicação, trabalhando juntos para identificar problemas e solucioná-los.

Extreme Programming é dinâmica e flexível, entre as suas "boas práticas" é possível citar: Comentários em código, diversas entregas pequenas, programação em pares, testes de aceitação, planejamento por pontos, refatoramento, presença constante do cliente, integração contínua, entre outros.

### 2.4 RUP

Segundo o documento descritivo do IBM Rational Unified Process, em mais de 20 anos de experiência trabalhando com clientes em milhares de projetos, o grupo IBM Rational construiu um framework de práticas comprovadas para desenvolvimento de softwares, extensíveis e escaláveis para se adaptarem às necessidades específicas dos projetos. O IBM Rational Unified Process (ou IBM RUP), é um framework abrangente que fornece práticas centradas em torno de um conjunto de princípios que a IBM achou que caracterizam as mais bem sucedidas organizações de sistemas e software do mundo:

* Desenvolver iterativamente

* Gerenciar requisitos

* Uso de componentes

* Modelar software visualmente

* Verificar qualidade

* Controlar mudanças 

Esses princípios ajudam a melhorar a produtividade individual e a colaboração de equipe para criar software e sistemas de alta qualidade, permitindo a construção de aplicações flexíveis que podem crescer e se adaptar.

"Para projetos menores com equipes fixas e tecnologia conhecida, os processos podem ser simples e informais. Para projetos maiores e distribuídos, que usam mais tecnologias e têm que estar de acordo com padrões mais rígidos, os processos se tornam mais complexos
e disciplinados." (IBM Rational Unified Process - Disponibilizado em: ftp://public.dhe.ibm.com//software/pdf/br/RUP_DS.pdf) 

Conforme o documento descritivo do IBM Rational Unified Process, a solução Rational Unified Process fornece uma coleção de processos que podem ser personalizados para abordar um conjunto diverso de necessidades de projeto e estilos de desenvolvimento. É capaz de suportar virtualmente qualquer tipo de esforço de desenvolvimento – de projetos ágeis e iterativos usando orientação de processo leve, a processos mais formais e regulatórios. É possível adaptar o processo ao tamanho e a distribuição da equipe de projeto, aos sistemas, diferentes e complexos das aplicações sendo desenvolvidas, e aos requisitos de conformidade.

## 3. Metodologia Montada
A metodologia adotada no projeto foi híbrida, baseada nos modelos do Scrum, Kanban, XP e RUP, além da inclusão de alguns artefatos pertinentes para demonstrar melhor nosso produto e como ele está sendo desenvolvido e rotinas pertinentes para organizar melhor o grupo.

Consideramos que uma metodologia híbrida se encaixa melhor no nosso contexto que possui uso de rotinas e artefatos diversos, além de ser possível sanar pontos fracos de uma metodologia usando alguns artefatos e rotinas de outras. Seja pelo excesso de documentação, no caso do RUP; precariedade de documentação, no caso do Scrum; ou pela falta de rotinas, no caso do XP e Kanban.

Nos sub-tópicos abaixo mostramos quais elementos das metodologias definidas acima foram aplicados no projeto.

### 3.1 Elementos SCRUM
As seguintes rotinas provindas do SCRUM foram utilizadas no projeto:

1. Sprints com uma semana de duração

2. Dailies três vezes por Sprint

3. Reunião de Planejamento da Sprint

4. Reunião de Review da Sprint

5. Reunião de Retrospectiva da Sprint

6. Reuniões com time-box

Os seguintes artefatos provindos do SCRUM foram utilizados no projeto:

1. Product Backlog

2. Documento de Planejamento da Sprint

3. Documento de Revisão da Sprint

4. Definição de pronto

O modelo de papéis do SCRUM foi utilizado no projeto, contando com Product Owner, Architect, Scrum Master e time de desenvolvimento, além de um papel extra de Dev-Ops para realizar as configurações de ambiente necessárias nos repositórios do grupo e garantir que o desenvolvimento ocorra de maneira fluída na máquina de qualquer desenvolvedor, para mais detalhes sobre as responsabilidades de cada papel consulte o [Roadmap de Papéis](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/projeto/RoadmapPapeis/).

Vale destacar que usamos o Product Backlog contendo histórias de usuário priorizadas usando a técnica MoSCoW (técnica em que a priorização de cada história é dada pelos verbos Must, Should, Could e Won't) e cada história é dividida em tasks e criada no repositório em que será executada. Dessa forma conseguimos manter as histórias como uma forma amigável de entender o produto e usamos das tasks para criar tarefas pequenas, passíveis de serem feitas em um sprint que comunicam diretamente com os desenvolvedores. Para mais detalhes consulte o [Backlog do Produto](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/produto/product-backlog/).

O SCRUM é a metodologia base do projeto, principalmente no que se refere a rotinas, provendo maneiras eficazes para controle do grupo durante o desenvolvimento. Os artefatos do SCRUM servem como base para realizar as rotinas.

### 3.2 Elementos Kanban
O grupo decidiu aplicar o Kanban para possibilitar o acompanhamento do progresso das tarefas definidas, através do plug-in ZenHub. As tarefas são bem documentadas e cada "card", que corresponde a issues do GitHub, pode receber comentários, com dúvidas e outros tipos de feedback.

As pipelines típicas de um Kanban são "To Do", "Doing" e "Done", no nosso contexto a pipeline de "Done" foi substituída por "Closed" que corresponde a uma issue finalizada, a pipeline "To Do" foi substituída pelo "Sprint Backlog" (tarefas da sprint atual) e "Product Backlog" (tarefas para as próximas sprints), enquanto a pipeline "Doing" se reparte em "In Progress" (tarefa em andamento) e "Review/QA" (tarefa aguardando revisão ou correções).

Aplicamos as seis práticas básicas do Kanban: Visualizar o fluxo de trabalho (workflow), limitar a quantidade de trabalho em andamento (WIP), gerenciar e medir o fluxo, tornar as políticas do processo explícitas, implementar loops de feedback e usar modelos para reconhecer oportunidades de melhoria, para extrairmos o máximo da técnica. Entramos em mais detalhes sobre isso no último tópico abordando métricas de desempenho.

### 3.3 Elementos XP
Os seguintes artefatos e rotinas do XP foram adotados: 

1. Comentários em Código

2. Entregas Pequenas

3. Programação em Pares

4. Planejamento por Pontos

5. Refatoramento

6. Integração Contínua

A equipe segue os cinco princípios básicos do XP: comunicação, simplicidade, feedback constante, coragem e respeito.

### 3.4 Elementos RUP
Os seis princípios básicos do RUP são seguidos pelo grupo, são eles:

1. Desenvolver iterativamente

2. Gerenciar requisitos

3. Uso de componentes

4. Modelar software visualmente

5. Verificar qualidade

6. Controlar mudanças 

Entre os princípios mencionados acima podemos destacar que o 4 não foi aplicado a risca com toda carga de UML (Unified Modeling Language, linguagem de notação para representar diversos diagramas) vinda do RUP, representações visuais foram feitas e estão localizadas no Documento de Arquitetura, mas o grupo escolheu a dedo quais diagramas são didáticos o suficiente e realmente trariam resultados eficazes para mostrar como o produto funciona.

Como o RUP é uma solução privada e altamente personalizável, o grupo decidiu apenas seguir alguns padrões e templates dessa metodologia. Podemos destacar templates de diversos documentos como visão, arquitetura, termo de abertura do projeto (TAP), entre outros.

## 4. Monitoramento
Para fazer o monitoramento do projeto e garantir que estamos efetuando isso corretamente usamos as nove áreas de conhecimento do PMBOK (Project Management Body of Knowledge), são elas: Integração, Escopo, Tempo, Custos, Qualidade, Recursos Humanos, Comunicações, Riscos e Aquisições. Abaixo segue uma breve descrição de como o mecanismo de gerência do grupo supre essas necessidades através das metodologias usadas e práticas extras. 

1. Integração - Garantimos o Gerenciamento da Integração através de alguns documentos provindos do RUP (TAP) e de rotinas e artefatos tanto do RUP (controlar mudanças) como do SCRUM (Sprint Planning e Review).

2. Escopo - Garantimos o Gerenciamento do Escopo através da Estrutura Analítica do Projeto, dos documentos de definição de produto (técnicas de definição e documento de visão) e do Backlog do Produto provindo do SCRUM.

3. Tempo - Garantimos o Gerenciamento do Tempo através do Roadmap do Produto, de alguns tópicos do Product Backlog e verificando as métricas de produtividade da equipe.

4. Custo - Garantimos o Gerenciamento dos Custos através de um documento individual que detalha todos os custos do projeto e da EVM que faz um monitoramento por sprint.

5. Qualidade - Garantimos o Gerenciamento da Qualidade do Produto através de uma série de decisões, práticas e métricas definidas no documento de qualidade. Algumas práticas vindas do XP (como pair programming, refatoração, integração contínua) e outras vindas do RUP (desenvolver iterativamente, uso de componentes, verificar qualidade) ajudam nesse gerenciamento.

6. Recursos Humanos - Garantimos o Gerencimento dos Recursos Humanos através do Kanban, das práticas e artefatos do SCRUM e dos princípios do XP, além de algumas diretrizes internas na forma como nos comunicamos com o grupo e levamos a matéria.

7. Comunicações - Garantimos o Gerencimento das Comunicações através de algumas ferramentas e grupos centralizadores no Telegram, Meet e Drive e através das issues do ZenHub e PRs do GitHub, o teor da nossa comunicação segue os princípios do XP.

8. Riscos - Garantimos o Gerencimento do Riscos através de um documento base dedicado a elicitar os riscos do projeto, associados a sua probabilidade, impacto, ações de prevenção e mitigação. A cada sprint a probabilidade e o impacto de cada risco são revistos e o planejamento é executado tendo esses riscos em vista.

9. Aquisições - Garantimos o Gerenciamento das Aquisições através de um documento individual que detalha todos os custos do projeto.

## 5. Métricas de Desempenho
Para mensurar o desempenho, estado e evolução da equipe dentro do projeto utilizamos alguns artefatos e métricas, são eles:

1. Burndown - Verificar quando as issues foram concluídas ou até quando elas foram colocadas no quadro de revisão
2. Velocity - Verificar a média de pontos que o grupo consegue entregar por sprint
3. Gráfico de Contribuições por Repositório - Verificar a constância das contribuições
4. Quadro de Conhecimentos - Monitorar a evolução do conhecimento dos membros nas tecnologias utilizadas
5. Planilha de Horas - Monitorar a carga de trabalho de cada membro

Através da análise desses cinco pontos acima de forma conjunta e a cada sprint o time consegue planejar as próximas atividades, verificar problemas no escopo, custo ou tempo do projeto e propor intervenções. Os documentos de Sprint Review contém uma seção dedicada a análise das métricas descritas acima.

## 6. Referências
* [Guia do Scrum](https://www.scrumguides.org/docs/scrumguide/v1/Scrum-Guide-Portuguese-BR.pdf)
* [Kanban](https://www.culturaagil.com.br/kanban-do-inicio-ao-fim/)
* [Extreme Programming](https://www.agilealliance.org/glossary/xp/)
* [IBM Rational Unified Process](ftp://public.dhe.ibm.com//software/pdf/br/RUP_DS.pdf)
* [Imagem Kanban](https://blog.caelum.com.br/wp-content/uploads/2016/01/kanban.jpg)
* [Imagem SCRUM](https://i2.wp.com/www.scrumportugal.pt/wp-content/uploads/como-funciona-o-scrum.png?fit=1300%2C570)
