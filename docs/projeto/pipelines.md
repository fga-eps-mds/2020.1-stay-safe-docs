# Pipelines

## API
![PIPELINE_API](../images/pipelines/pipeline_api.png)

### Etapas
* **BUILD:** É executado a build do projeto.
* **PYLINT:** É executado o Pylint a fim de verificar a qualidade de código e possíveis bugs. Nessa etapa é usado a folha de estilo pep8 como base.
* **TESTES:** São executados os testes unitários do projeto usando o pytest, após isso, é executado a cobertura de testes usando o Coverage.py

## Front-end
![PIPELINE_FRONT](../images/pipelines/pipeline_front.png)

### Etapas
* **BUILD:** É executado a build do projeto usando o expo
* **ESLint:** É executado o ESLint a fim de verificar a qualidade de código e possíveis bugs.
* **TESTES:** São executados os testes unitários do projeto usando o Jest.
