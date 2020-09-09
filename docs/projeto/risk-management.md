# Plano de Gerenciamento de Risco

## 1. Introdução
O plano de gerenciamento de riscos trata da execução de atividades de gerenciamento de risco. Neste documento o objetivo é facilitar a visualização dos riscos através da identificação e mapeamento, para auxiliar na tomada de decisões relacionadas, a fim de que a produtividade do projeto possa ser mantida e ele seja concluído.

## 2. Categoria de Riscos
Riscos são condições incertas que, caso ocorram, podem trazer benefícios ou maleficios aos objetivos do projeto. Como existem diversos vetores que possibilitariam essas ocorrências, foram agrupadas as possíveis classificações dos riscos em quatro grandes categorias, são elas:

* **Técnico:** Abordam tecnologia, requisitos, complexidade, desempenho, interfaces, confiabilidade e qualidade.
* **Externo:** Abordam riscos relativos ao cliente, mercado, ambiente de trabalho e fatores pessoais.
* **Organizacional:** Abordam a priorização, recursos e dependências do projeto.
* **Gerência:** Abordam planejamento, controle, estimativa e comunicação.

## 3. Análise Quantitativa

### 3.1. Probabilidade
**Probabilidade** | **Intervalo** | **Peso**
:---------------: | :-----------: | :------:
**Muito Alta**    |   65 a 100    |    5
**Alta**          |   51 a 65     |    4
**Média**         |   31 a 50     |    3
**Baixa**         |   11 a 30     |    2
**Muito Baixa**   |   0 a 10      |    1

### 3.2. Impacto
Para se quantificar o impacto do risco no projeto o custo, o tempo, o escopo e a qualidade devem ser levados em conta.

**Impacto**       |                     **Descrição**                      | **Peso**
:---------------: | :----------------------------------------------------: | :------:
**Muito Alto**    | O impacto inviabiliza o projeto                        |    5
**Alto**          | Há grande impacto no desenvolvimento do projeto        |    4
**Médio**         | Possui certo impacto porém é facilmente recuperado     |    3
**Baixo**         | Pouco impacto no desenvolvimento do projeto            |    2
**Muito Baixo**   | Impacto pouco expressivo no desenvolvimento do projeto |    1

### 3.3. Prioridade
Baseando-se nas estimativas de impacto e probabilidade é possível calcular a prioridade dos riscos. A partir desses valores é determinada a urgência da inicialização de medidas de mitigação e resolução dos riscos.

**Probabilidade x Impacto** | **Muito Baixo** | **Baixo** | **Médio**  | **Alto** | **Muito Alto**
:-----------------------: | :-------------: | :-------: |:----------:|:--------:|:------------: 
**Muito Baixa**           |        1        |    2      |      3     |    4     |      5
**Baixa**                 |        2        |    4      |      6     |    8     |      10
**Média**                 |        3        |    6      |      9     |    12    |      15
**Alta**                  |        4        |    8      |      12    |    16    |      20
**Muito Alta**            |        5        |    10     |      15    |    20    |      25

#### 3.3.1 Valor de Prioridade
**Prioridade** | **Intervalo** 
:------------: | :-----------: 
**Muito Alta** |     21 a 25    
**Alta**       |     16 a 20   
**Média**      |     11 a 15     
**Baixa**      |     6 a 10   
**Muito Baixa**|     1 a 5      

## 4. Identificação dos Riscos

### R01 - Dificuldades da equipe com as novas tecnologias inseridas
**Causa:** Inexperiência de alguns membros
**Consequência:** Surgimento de dividas técnicas pela dificuldade em realizar os objetivos propostos
**Impacto:** 4
**Probabilidade:** 4
**Prioridade:** 16
**Categoria:** Técnico
**Ação Preventiva:** Seleção de alunos que já tenham tido algum contato com as tecnologias
**Ação Reativa:** Realização de treinamentos e pareamentos efetivos

### R02 - Divergência de horários entre membros da equipe
**Causa:** Membros com grades horárias muito distintas
**Consequência:** Dificuldade para reunir toda a equipe e relizar os pareamentos
**Impacto:** 4
**Probabilidade:** 5 
**Prioridade:** 20
**Categoria:** Gerência
**Ação Preventiva:** Elaboração de planilhas de controle de horários
**Ação Reativa:** Planejar os pareamentos e reuniões baseado na planilha de horários

### R03 - Desistência da disciplina
**Causa:** Sobrecarga dos alunos
**Consequência:** Equipe desfalcada e sobrecarga dos membros que permanecem na matéria
**Impacto:** 5
**Probabilidade:** 2
**Prioridade:** 10
**Categoria:** Gerência
**Ação Preventiva:** Incentivar a participação dos membros e a união do time
**Ação Reativa:** Redistribuir tarefas e refazer parte do planejamento do projeto

### R04 - Alteração do escopo
**Causa:** Mudança no mercado, surgimento de novos requisitos
**Consequência:** Alterações no projeto inicial e no planejamento do projeto
**Impacto:** 4
**Probabilidade:** 5
**Prioridade:** 20
**Categoria:** Gerência
**Ação Preventiva:** Refinar constantemente os requisitos e manter as funcionalidades atualizadas
**Ação Reativa:** Redefinir o escopo e redistribuir tarefas

Alteração das tecnologias
Presença dos membros durante Daily e Reuniões de planejamento
Falta de cliente real
Dependência entre as atividades
Falta de integração entre a equipe
Irresponsabilidade dos membros com o projeto
Problemas com estações de trabalho  

### R12 - Erros durante o planejamento das atividades
**Categoria:** Gerência  
**Causa:** Falta de experiência da equipe de gerência  
**Consequência:** Trabalho mal distribuído entre os membros da equipe  
**Ação Preventiva:** Conhecer bem a capacidade da equipe e as necessidades do projeto   
**Ação Reativa:**  Avaliar as métricas do projeto para regular os próximos planejamentos  
**Probabilidade:** Alta  
**Impacto:** Alto  
**Prioridade:** Alta

### R13 - Dados deixarem de ser fornecidos pelas secretarias
**Categoria:** Externo  
**Causa:** Decisões das secretarias  
**Consequência:** Impossibilidade de atualização de uma funcionalidade importante do projeto  
**Ação Preventiva:** -  
**Ação Reativa:** Procurar outras fontes de dados ou deixar de fornecer a funcionalidade   
**Probabilidade:** Média  
**Impacto:** Muito alto   
**Prioridade:** Média  

### R14 - Falta de gratuidade do Google Maps
**Categoria:** Externa  
**Causa:** Políticas da Google  
**Consequência:** Atraso nas funcionalidades que usam exibição de mapas  
**Ação Preventiva:** Fazer essas funcionalidades de forma que sejam fáceis de integrar com outra api de mapa  
**Ação Reativa:** Procurar outras alternativas gratuitas de uso de mapas  
**Probabilidade:** Média  
**Impacto:** Alto  
**Prioridade:** Média  

### R15 - Problemas pessoais ou de saúde relacionados a pandemia da COVID-19
**Categoria:** Externo  
**Causa:** Doença infeciosa COVID-19  
**Consequência:** Capacidade de trabalho da equipe prejudicada e atrasos no cronograma  
**Ação Preventiva:** Seguir as recomendações de prevenção da Organização Mundial da Saúde  
**Ação Reativa:** Remanejamento das atividades e apoio ao(s) membro(s) afetado(s)  
**Probabilidade:** Alta  
**Impacto:** Alto  
**Prioridade:** Alta  

### R16 - Conflito com outras disciplinas
**Categoria:** Organizacional  
**Causa:** Necessidade, sendo alunos os membros da equipe, de cursar outras disciplinas para conclusão da graduação  
**Consequência:** Atraso nas entregas ou entregas mal feitas  
**Ação Preventiva:** Organizar os prazos e fazer um planejamento  
**Ação Reativa:** Priorização das atividades  
**Probabilidade:** Muito alta  
**Impacto:** Médio  
**Prioridade:** Média

### R17 - Problemas com a estação de trabalho
**Categoria:** Técnico  
**Causa:** Falta de acesso a uma boa internet e/ou a um computador funcionando  
**Consequência:** Capacidade de trabalho da equipe prejudicada e atrasos no cronograma  
**Ação Preventiva:** -  
**Ação Reativa:**  Remanejamento das atividades e revisão do cronograma  
**Probabilidade:** Baixa  
**Impacto:** Alta  
**Prioridade:** Baixa

### R18 - Descumprimento de alguma legislação
**Categoria:** Gerência  
**Causa:**  Falta de conhecimento jurídico da equipe de gerência  
**Consequência:** Cometer alguma ilegalidade  
**Ação Preventiva:**  Fazer um estudo da legislação associada ao escopo do projeto  
**Ação Reativa:**  Procurar apoio jurídico profissional  
**Probabilidade:** Média  
**Impacto:** Muito alto  
**Prioridade:** Média


## 5. Referências
* RODRIGUES, Eli. EAR para projetos de software. Disponível em https://www.elirodrigues.com/2013/09/21/gerenciamento-de-riscos-ear-para-projetos-de-software/. Acesso em 30 set 2019.


