# Planejamento

# Introdução
Testes de aceitação são um dos principais tipos de testes usados para validar o desenvolvimento de requisitos, que são construídos ao longo do processo de percepção do produto. O resultado desses testes devem demonstrar que o sistema é capaz de executar as funcionalidades existentes de forma adequada e coerente em termos de tempo de resposta e validade dos resultados, já a construção desses testes se dá a partir de situações de uso do próprio sistema. Além disso, os testes de aceitação podem  também avaliar a aplicação quanto à navegabilidade, usabilidade e acessibilidade, nesse sentido serão propostas algumas tarefas e, durante a sua realização, os avaliadores que compoẽm o time deverão atentar-se à identificação de problemas ou dificuldades do usuário ao navegar no app. O intuito deste documento é relatar desde os objetivos a quais serão os testes aplicados e como funcionarão os critérios de sucesso.        

# Objetivo
O principal objetivo da realização desses testes é verificar aspectos citados anteriormente, como acessibilidade, navegabilidade e usabilidade. Para isso, pautamos nossos objetivos de forma que os problemas relacionados a esses aspectos, caso existam, sejam evidenciados durante as avaliações. As grandes áreas que são compreendidas nessas verificações são:          
* **Precisão**: Quantos erros a pessoa cometeu? E eles foram fatais ou a pessoa conseguiu se recuperar com as informações recebidas pelo sistema?              
* **Desempenho**: Quanto tempo e quantos passos são necessários para que a pessoa complete tarefas básicas?       
* **Lembrança**: O quanto a pessoa se lembra mais tarde ou depois de períodos sem usar?           
* **Resposta Emocional**: Como a pessoa se sentiu depois de completar a tarefa? A pessoa estava confiante ou estressada?        

O entendimento do usuário em relação às funcionalidades, à facilidade ou não em encontrar funcionalidades de acordo com a disposição na tela e a navegação, do login à execução das principais funcionalidades, serão os pontos principais de observação. Para padronizar esse processo, serão determinadas quais informações serão passadas ao usuário e quais os fluxos de teste.         

# Usuários de Teste
Para que fosse possível o desenvolvimento da aplicação mesmo que sem um cliente real, foram criados perfis diversificados de usuários fictícios utilizando a técnica de [personas](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/produto/product-definition/). Para realizar os testes de aceitação é pretendido que a equipe encontre pessoas que possuam um perfil semelhante ao das personas, sendo estimada a participação de pelo menos cinco usuários e que o ambiente onde acontecerá os testes seja informal, havendo o mínimo de intervenções externas possíveis durante a realização dos mesmos.

# Modelo de Relatório
Algumas características que seriam variáveis em cada relatório, como quantidade de membros presentes e quantidade de usuários, já foram pré-definidas devido ao cenário proporcionado pela pandemia da COVID-19. Não será possível sair em busca de muitos testadores e nem reunir membros da equipe para as avaliações, visando manter o distanciamento social e evitar a propagação da doença. O tempo médio e a conclusão, ou não, da realização de cada tarefa serão registrado através do desenvolvimento de um tabela com os seguintes campos:



|                        | Tarefa 1 | Tarefa 2 | Tarefa 3 | Tarefa 4 | Tarefa 5 | Tarefa 6 | Tarefa 7 | Tarefa 8 | Tarefa 9 |
|:----------------------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
| **Não conseguiu realizar** |          |          |          |          |          |          |           |           |           |
| **Sim, com dificuldade**   |          |          |          |          |          |          |           |           |           |
| **Sim, com facilidade**    |          |          |          |          |          |          |           |           |           |      
| **Tempo de execução**      |          |          |          |          |          |          |           |           |           |     

Ao final da avaliação os testadores serão submetidos às seguintes perguntas:      
1. Como você avaliaria sua experiência ao utilizar o aplicativo? (de 1 a 5, como 1 sendo uma experiência muito ruim e 5 sendo uma experiência muito boa)       
2. Você utilizaria esse app no seu dia-a-dia? Por que?         
3. Como você avalia a identidade visual do aplicativo?        
4. Acha que os ícones são representativos?        
5. Tem alguma reclamação sobre alguma tela específica?     
6. Sentiu falta de alguma instrução/informação?
7. As funcionalidades apresentadas no aplicativo corresponderam as suas expectativas em relação a proposta do aplicativo?      

Com o propósito de relatar o feedback, para cada pergunta será desenvolvida uma lista com as respostas de cada testador e uma análise sobre todas as respostas.

# Roteiro 
## Instrução Inicial
Todos os testes deverão ser iniciados com a exposição do objetivo do produto, qual o contexto do desenvolvimento e qual o objetivo do teste que será realizado, enfatizando que o produto será avaliado e não a capacidade do usuário de realizar as tarefas. Além disso, é necessário:        
* Como se dará o andamento do teste;       
* Solicitar que o usuário expresse sempre o que está pensando e o que está tentando fazer;      
* Relembrar o usuário de que o produto está em processo de aprimoramento, então não deve se preocupar em criticar pois sua crítica será de extrema importância para o resultado final.       

## Realização de Tarefas
* Tarefa 1: Será solicitado que o usuário realize seu cadastro na aplicação.      
* Tarefa 2: Será solicitado que o usuário Cadastre uma ocorrência.      
* Tarefa 3: Será solicitado que o usuário Visualize uma ocorrência.     
* Tarefa 4: Será solicitado que o usuário visualize estatísticas do crime de roubo a veículo.
* Tarefa 5: Será solicitado que o usuário visualize estatísticas de uma cidade.
* Tarefa 6: Será solicitado que o usuário avalie um bairro.    
* Tarefa 7: Será solicitado que o usuário filtre os pins que aparecem no mapa por um crime específico.        
* Tarefa 8: Será solicitado que o usuário edite e apague uma ocorrência e uma avaliação de bairro.       
* Tarefa 9: Será solicitado que o usuário cadastre e apague um local favorito.      

## Critérios de Sucesso   
* O sucesso de cada tarefa é o usuário conseguir executá-la. 
* Para cada uma das tarefas foi determinado um tempo mínimo, então caso usuário consiga executá-la dentro do tempo, demonstrará um bom padrão da usabilidade e reforçará o resultado positivo. 
* Feedbacks dos testadores serem positivos(em sua maioria) também demonstrarão o sucesso dos testes.      
Os resultados dos testes bem como as mudanças consequentes serão resgistradas no documento de [Resultados](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/produto/Testes_de_Aceitação/results/)

### Heurísticas de Nielsen
Conforme descrito no [documento de qualidade](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/produto/quality/) do Stay Safe, os testes avaliarão se a aplicação atende as Heurísticas de Nielsen. Caso atenda, demonstra então que possui boa navegabilidade e usabilidade.

### Diretrizes de Acessibilidade 
Também conforme o [documento de qualidade](https://fga-eps-mds.github.io/2020.1-stay-safe-docs/produto/quality/), caso a equipe encontre pessoas portadoras de necessidades especias que possam realizar os testes, será avaliada a acessibilidade da aplicação conforme as recomendações de acessibilidade da World Wide Web Consortium. Isso permitirá saber o quão inclusivo é o Stay Safe.

# Referências Bibliográficas     
* Curso UX e Usabilidade aplicados em Mobile e Web, Capítulo 11, Apêndice: [Testes de Usabilidade](https://www.caelum.com.br/apostila-ux-usabilidade-mobile-web/usabilidade/#preparao-prvia);              
* [Teste de usabilidade](https://www.uiux.pt/2019/09/26/testes-de-usabilidade/). Quantos users? Como medir? Para que serve?      
* Modelos de [Testes de Aceitação do Usuário](https://cjjcastro.gitlab.io/2019-1-hubcare-docs/project-quality-management/acceptance-test-model/)      
