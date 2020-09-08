# Plano de Gerência e Configuração de Software

## 1. Introdução
Este documento tem como objetivo apresentar as ferramentas, políticas e regras adotadas pelo projeto para auxiliar quem deseja contribuir.

## 2. Ferramentas 
| Ferramenta | Finalidade |
|---|---|
| GitHub | Hospedagem e versionamento de código |
| GitHub Actions | Ferramenta de integração contínua |
| GitHub Pages | Repositório visual da documentação |
| Docker | Ferramenta de isolamento de ambiente |
| Docker-Compose | Ferramenta de gerenciamento de containers |
| Flask | Framework de desenvolvimento backend |
| PyUnit | Framework de teste Python |
| Coverage py | Ferramenta de cobertura de código Python |
| Pylint | Ferramenta de análise de código Python |
| React Native | Framework de desenvolvimento frontend |
| Jest | Framework de teste JavaScript |
| ESLint | Ferramenta de análise de código JavaScript |
| Prettier | Formatador de código automático |

## 3. Políticas

### 3.1 Política de Commits
Os commits devem ser atômicos (uma contribuição pequena para resolver um problema específico). A mensagem do commit deve relatar o que foi feito de maneira sucinta e direta, além disso ela precisa estar em inglês, começar com um verbo e com a primeira letra maiúscula. 

Contribuições feitas por mais de uma pessoa devem conter o comando "Co-authored-by" para identificar todos os autores envolvidos.

Exemplo de contribuição feita por um autor:

    git commit -m "Add database diagram image."

Exemplo de contribuição feita por mais de um autor:

    git commit -m "Create user model.

    Co-authored-by: Pessoa <emailgit@email.com>"


### 3.3 Política de Issues
Caso encontre um bug ou tenha alguma sugestão de melhoria para o software é possível criar uma issue seguindo os passos abaixo. 

1. Escolha o tipo de issue a ser criado (funcionalidade, documentação ou correção de bug)
2. Escreva um título sucinto para a issue
3. Preencha a descrição da issue seguindo os passos e as orientações do template que será mostrado

As issues deverão ser escritas em inglês.

Se a issue tratar de uma história do Backlog do Produto, seu título deve ser o código da história mais a descrição da história. O criador da issue também pode preencher informações adicionais (épico, executores, marco) desta caso as possua.

### 3.4 Política de Branches

### 3.2 Política de Pull Request
Para realizar um Pull Request (PR) para o repositório é necessário seguir os passos abaixo.

1. Ao resolver uma issue suba suas contribuições e crie um Pull Request
2. Escreva um título sucinto para o PR 
3. Preencha a descrição do PR seguindo os passos e as orientações do template que será mostrado
4. Ligue o PR com a issue que ele resolve
5. Preencha informações adicionais caso possua (executores, revisores, etc)

Ao realizar um PR nos repositórios de documentação a nova branch deve ser comparada e merjada com a master, enquanto nos repositórios de código ela deve ser comparada e merjada com a devel.

### 3.5 Política de Documentação

### 3.6 Versionamento
Versionamento do código

O versionamento da documentação deve seguir um padrão X.Z, onde X e Z são numerais inteiros não negativos que crescem em ordem crescente. Ao fazer grandes incrementos a variável X cresce (1.0, 2.0, 3.0) e ao fazer pequenos incrementos a variável Z cresce (1.1, 1.2, 1.3), ambas variáveis começam em zero e crescem de um em um. Ao subir a versão de X o valor de Z volta pra zero (1.4 -> 2.0). O documento só entra na versão 1.0 se naquele momento ele estiver teoricamente finalizado.

## 4. Política de Aprovação