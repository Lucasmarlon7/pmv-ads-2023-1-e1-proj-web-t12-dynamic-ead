# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

O propósito do projeto é desenvolver uma Aplicação Web que ajude os alunos a criarem uma rotina de estudos de fácil manejo e entendimento. Para atender às necessidades dos usuários, a solução proposta inclui ferramentas que permitem a criação de um cronograma personalizado de estudos, com controle de atividades e prazos de entrega, além de um sistema de "focus time" para ajudar a manter a concentração. 

No desenvolvimento do projeto foram utilizadas técnicas como a definição do diagrama de personas, análise de concorrência, brainstorming, prototipação, modelagem de dados, histórias de usuários, requisitos funcionais e não funcionais, além das restrições, que foram montadas baseadas no tempo hábil para entrega.

## Personas

![Imagem persona Thiago Nunes](img/thiago-nunes.png)

![Imagem persona Amanda Oliveira](img/amanda-oliveira.png)


## Histórias de Usuários


|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`     | PARA ... `MOTIVO/VALOR`                         |
|--------------------|--------------------------------------- |-------------------------------------------------|
|Thiago Nunes        | Montar cronogramas.                    |  Organizar meu plano de estudos.                |
|Thiago Nunes        | Reduzir distrações ao estudar.         |  Evitar procrastinação e perdas de desempenho.  |
|Amanda Oliveira     | Simplificar o gerenciamento de tarefas.|  Otimizar meu tempo.                            |



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito                                                     | Prioridade |
|------|----------------------------------------------------------------------------|------------|
|RF-001| O sistema deve permitir ao usuário cadastrar, editar e deletar atividades. |    ALTA    | 
|RF-002| O sistema deve permitir a consulta do progresso de atividades.             |    ALTA    | 

### Requisitos não Funcionais

|ID     | Descrição do Requisito                                                                 | Prioridade |
|-------|----------------------------------------------------------------------------------------|------------|
|RNF-001| O sistema deve ser responsivo para se adaptar a dispositivos móveis.                   |    MÉDIA   | 
|RNF-002| O sistema deve permitir que o usuário utilize o sistema sem necessidade de treinamento.|    ALTA    |
|RNF-003| O sistema deve ser possível de ser migrado para frameworks futuramente.                        |    MÉDIA   |



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                   |
|--|-------------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre.      |
|02| O projeto deve ser desenvolvido em HTML, CSS E JAVASCRIPT.  |
|03| Não pode ser desenvolvido um módulo de backend.             |



