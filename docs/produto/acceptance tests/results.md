# Teste de Aceitação - Primeiro Resultado

### Introdução
Baseado no [documento de planejamento](https://github.com/fga-eps-mds/2020.1-stay-safe-docs/blob/93-conduct-acceptance-tests/docs/produto/acceptance%20tests/planning.md) foram realizados testes com 7(sete) pessoas para testarem as funcionalidades descritas anteriormente.

### Data da relização dos testes
Foram realizados os testes nos dias 11, 12 e 13 de novembro de 2020.

### Personas
Para a realização dos testes foram procurados perfis compatíveis com os das personas desenvolvidas pelo grupo, no entanto , devido à pandemia e aos protocolos de distanciamento social, não foi possível encontrar testadores para todos os perfis. Em contrapartida, foram selecionadas pessoas experientes em diferentes áreas dentro de desenvolvimento de software que abrangessem conhecimentos que a equipe não possui, como design e UX/UI, e também desenvolvedores experientes em back-end. Além de pessoas da área, também foram selecionados testadores leigos para que os feedbacks pudessem ser diversificados e gerados de diferentes óticas.

### Tarefas

A quantidade de pessoas que realizaram ou não cada tarefa proposta foi contabilizada na tabela abaixo:

|                        | Tarefa 1  | Tarefa 2  | Tarefa 3  | Tarefa 4 | Tarefa 5  | Tarefa 6 | Tarefa 7 | Tarefa 8| Tarefa 9|
|:----------------------:|:---------:|:---------:|:---------:|:--------:|:---------:|:--------:|:--------:|:--------:|:--------:|
| **Não conseguiu realizar** |     0     |     1     |     1     |     1    |     1     |     3    |     0    |    0    |    0   |
| **Sim, com dificuldade**   |     1     |     2     |     1     |     4    |     4     |     2    |     2    |    0    |    0   |
| **Sim, com facilidade**    |     6     |     4     |     5     |     2    |     2     |     2    |     1    |    3    |    3   |
| **Tempo de execução(média em segundos)**|     59   |     78   |     15    |     75   |     54   |     48     |    48   |    35    |    40    |

*As últimas 3 tarefas foram realizadas apenas com 3 testadores, pois foram adicionadas no decorrer dos testes.*

#### Conclusão
Podemos concluir com base nos feedbacks das realizações das tarefas que as tarefas 1, 2 e 3 foram mais simples para os testadores e a partir da tarefa 4 eles sentiram uma dificuldade principalmente com a modal de filtros, que inferimos que possui funcionalidades que não pertencem a ela.

### Perguntas de Feedback
1. **Como você avaliaria sua experiência ao utilizar o aplicativo? (de 1 a 5, como 1 sendo uma experiência muito ruim e 5 sendo uma experiência muito boa)**
<center><img src='https://i.imgur.com/euv91D7.png'></center>

#### Conclusão
Podemos concluir com base nos feedbacks que o aplicativo possui uma experiência agradável para os usuários, mas que podemos melhorar em alguns pontos críticos.

2. **Você utilizaria esse app no seu dia a dia? Por Quê?**
* Sim, pois ando muito sozinho e às vezes para lugares que não conheço e desejo saber qual a segurança desse lugar.
* Sim, parece interessante para quem usa transporte público e transita em vias públicas constantemente.
* Sim, porém baseando-se apenas no pins. A estatística das RAs são apenas para momentos específicos.
* Não, pois não acha as funcionalidades dentro dele.
* Sim, com certeza, achou a ideia muito boa.
* Sim, gostou da proposta.
* Sim, achou uma boa ideia.
#### Conclusão
Podemos concluir com base nos feedbacks que os usuários acham o aplicativo útil e que possui utilidade no dia a dia.      

3. **Como você avalia a identidade visual do aplicativo?**
* Boa, porém com falha nos contrastes dos textos com os botões no modo escuro.
* Gostou das cores e da falta de poluição nas telas.
* Muito boa, bem diferente e não é saturada.
* Legal, boas cores, remete bem ao tema.
* Boa, está bonito.
* Padrão, bonita.
* Bonita.
#### Conclusão
Podemos concluir com base nos feedbacks que a identidade visual do aplicativo está boa e suas cores agradáveis, com esceção de pequenos pontos em alguns botões.      

4. **Acha que os ícones são representativos?**        
* Sim, exceto o de filtro, pois engloba muitas funcionalidades que não atribuiria a ele.
* Sim, com exceção do ícone de registrar ocorrência.
* Sim, com exceção do ícone dos fitros.
* Sim, com exceção do ícone dos fitros.
* Sim, com exceção do ícone dos fitros.
* Mais ou menos.
* Sim.
#### Conclusão
Podemos concluir com base nos feedbacks que os ícones são representativos com exceção do ícone de filtro, que não exemplifica bem suas funcionalidades.     

5. **Tem alguma reclamação sobre alguma tela específica?**     
* Tela de Login: Diferença de linguagem no título dos campos(username, senha).<br/>Tela de Cadastro de Ocorrência: roubo a transeunte não ficou explícito; a barra de rolagem nos tipos de ocorrências não aparece bem e não indica que a tela tem uma rolagem; título do campo vítima não representa bem o campo; título do campo de BO não deixa claro o campo.<br/>Tela Home: falta de intuitividade do botão de registrar ocorrência; ícone de filtro sobrepõe o ícone de localização do usuário; as bordas do mapa de calor são muito grossas; para marcação do filtro é necessário clicar só no círculo, não há a possibilidade de clicar no nome; mapa recarrega quando a tela de detalhes da ocorrência é fechada. Ao clicar no filtro do mapa de calor ele recarrega o mapa para os pins.
* A ocorrência fica clicável na hora de selecionar um local favorito. Ícones se sobrepõe no mapa. O mapa volta para o mapa de pins ao tentar filtrar o mapa de calor por uma segunda vez. A distância do mapa ao centralizar no DF deixa ele meio longe, precisa dar zoom. Existe uma borda escura no canto inferior esquerdo da navbar na tela do mapa.
* Quando clica em ocorrencia e volta pro mapa, volta pro lugar onde esta no mapa.
* Pra voltar pro mapa inicial quando esta no mapa de calor é dificil.
* Não.
* Apenas a tela em branco.
* Não.
#### Conclusão
Podemos concluir com base nos feedbacks que o aplicativo possui melhorias a serem feitas em muitas telas, porém na maioria dos casos são mudanças pontuais e de linguagens que não interferem no funcionamento geral da tela.

6. **Sentiu falta de alguma instrução/informação?**
* Nome dos filtros não é intuitivo. Não aparece o nome da RA no mapa de calor. Não há a informação do intervalo de tempo do mapa de calor. Não ficou explícito que ao clicar na RA no mapa de calor aparece as estatísticas. Dificuldade de achar os bairros.
* De instruções falando qual as funcionalidades do app, como um guia caso quisesse realizar alguma delas.
* Sim, pra saber quais funcionalidades tem e como fazer elas.
* Sim, algum guia para chegar nas funcionalidades procuradas.
* Sim, na hora dos filtros fiquei um pouco perdido.
* Sim, de tutoriais de instrução.
* Não.      

#### Conclusão 
No geral os testadores sentiram a necessidade de instruções claras de quais seriam as funcionalidades do app e como acessá-las, além de não terem considerado algumas perguntas tão claras.

7. **As funcionalidades apresentadas no aplicativo corresponderam as suas expectativas em relação a proposta do aplicativo?**
<center><img src='https://i.imgur.com/ubBRSDt.png'></center>

#### Conclusão
Podemos concluir com base nos feedbacks que o aplicativo possui boas funcionalidades e que o usuário acha útil para o objetivo do aplicativo.

## Definição de Ajustes e Melhorias
Tendo como partida as sugestões propostas pelos testadores e as observações feitas durante a execução dos testes, alguns ajustes foram discutidos pela equipe e definidos como atividades a serem realizadas nas próximas sprints:

* Mudar o nome da aba “local” na modal de filtros.
* Realizar um Guia Inicial para o usuário na primeira vez em que ele abrir o aplicativo.
* Padronizar o idioma do aplicativo para português nas telas de cadastro e login de usuário.
* Mudar os campos "Roubo a Transeunte" para "Roubo a Pedestre".
* Mostrar o mapa de calor do DF mais aproximado, com um zoom maior.
* Melhorar título dos campos "Vítima" e "Boletim de Ocorrência" para um texto mais explícito.
* Melhorar o contraste do texto de alguns botões no modo escuro.
* Adicionar informações sobre os anos das estatísticas visualizadas.
* Realocar ícone dos filtros.
* Deixar clicável o nome dos filtros na modal de filtros.
* Melhorar funcionamento do mapa em relação à modal de filtros.
* Refatorar a tela Home para que possua dois mapas diferentes, cada um com sua funcionalidade, e um botão de navegação entre esses dois mapas.
* Deixar barra de rolagem sempre visível nos tipos de ocorrências e melhorar seu contraste no modo escuro.
* Remover os pins do mapa de selecionar locais favoritos.
* Não ser redirecionado para a própria localização ao cadastrar a ocorrência e sim continuar de onde começou o cadastro.