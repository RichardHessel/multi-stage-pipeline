# multi-stage-pipeline
Pipeline yaml para executar ci/cd no azure devops

O pipeline foi criado com o intuito de colocar em prática os aprendizados adquiridos no estudo da documentação disponibilizada pela microsoft.
Foram criados 3 arquivos:
- vars.sonar.yml: um arquivo que guarda as variáveis necessárias para execução do sonar, o objetivo principal foi demonstrar a possibilidade do uso de variáveis no azure pipelines em um arquivo desacoplado.
- default_stages.yml: arquivo que contempla os passos que precisam ser executados e tem por objetivo demonstrar a possibilidade de se reaproveitar os stages/jobs/steps entre diversos pipelines
- azure-pipelines.yml: possui a definição padrão para execução do pipeline em um determinado projeto, demonstra a utilização de variáveis e passos externos ao arquivo. 

O aprendizado adquirido foi compartilhado em uma story criada por mim, no medium, que pode ser acessada pelo [link](https://medium.com/@richardhessel.r/desenvolvendo-um-pipeline-multi-stage-com-o-azure-pipelines-e96cb87f2437). 
