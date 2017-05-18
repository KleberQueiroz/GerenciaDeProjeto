## _Scrum_

### Papéis

| Scum Master | Product Owner | Tracker | Developer |
|-----------------------------------|--------------------------------------|--------------------------------|-----------------------------------|
| Assegurar Práticas do Scrum | Gerenciar Backlog | Garantir a qualidade de código | Desenvolver Histórias de Usuários |
| Controlar o tempo das reuniões | Validar Histórias de Usuário | Coleta de Métricas da Sprint | Buscar o auto-gerenciamento |
| Assegurar rotação do conhecimento | Auxiliar no planejamento das sprints | Gerenciar branches | Disseminar conhecimento |
| Garantir a colaboração da equipe |  | Fazer merges de branches ao final da sprint |  |
| Tirar obstáculos para o projeto |  |  |  |
### Reuniões Diárias

#### Daily Meeting

<p align="justify">Nesse primeiro momento, foi seguida a metodologia proposta na disciplina, onde as reuniões são diárias. Na terça, quinta e sábado as reuniões serão presenciais, e nos demais dias, através do canal do Slack "Daily".

### Reunião Semanal

<p align="justify">Ao final de cada Sprint a equipe se reunia para fazer a Sprint Review, Retrospectiva e o Planejamento da próxima sprint. Na Sprint Review será analisado o que foi alcançado no Sprint. Na Retrospectiva, a equipe conversava acerca dos pontos positivos, negativos e propostas de melhoria que deveriam ocorrer para melhor andamento do projeto. No planejamento, é escrita a descrição de cada história pela equipe, os critérios de aceitação pelo PO e logo em seguida eram divididas entre o time de desenvolvimento.

### Artefatos

<p align="justify">Dois artefatos foram produzidos e gerenciados pelo Product Owner: o Product Backlog, que contém todas as histórias derivadas, e o Backlog da Sprint, com as histórias planejadas para a Sprint atual.

### Duração das Sprints

<p align="justify">Conforme solicitado na disciplina, foram executadas Sprints com duração de uma semana cada.

## Extreme programing (XP)

### Programação em Pares

<p align="justify">Uma das práticas utilizadas no projeto foi o pareamento.

### Integração Contínua e Deploy Contínuo

<p align="justify">Outra prática utilizada no projeto foi a Integração Contínua e Deploy Contínuo. A Integração Contínua é executado automaticamente pelo CircleCI sempre que uma mudança fosse realizada e colocada no repositório oficial do GitHub e em seguida era feito o Deploy da Software no Heroku.

## Ferramenta de Acompanhamento da Sprint

<p align="justify">Inicialmente foi realizada uma pesquisa comparativa entre 3 ferramentas de controle de sprint. Foram o ZenHub, o Waffle e o HuBoard. Foram testas as 3 ferramentas e com a ajuda de um comparativo [link](https://stackshare.io/stackups/huboard-vs-waffle-io-vs-zenhub). 

<p align="justify">No final, houve um impasse entre a ferramenta ZenHub e Waffle que são eficientes para o nosso projeto. Foi escolhido o ZenHub por não precisar sair do repositório para o controle da sprint, além de ser integrado com o slack.

[![Captura de tela de 2017-04-29 11-57-31.png](https://s23.postimg.org/6olmz8hbv/Captura_de_tela_de_2017-04-29_11-57-31.png)](https://postimg.org/image/lxbkd0b07/)

## Kanban

<p align="justify">Foi utilizado o Kanban para a equipe ter uma melhor visibilidade do projeto de forma que todos os integrantes do projeto possam visualizá-lo e modificá-lo de forma rápida e fácil, além de que qualquer pessoa interessada no projeto também possa visualizá-lo facilmente. Para facilitar esta visualização, foi usada a ferramenta ZenHub conectada ao Git. Na aba de Boards é possível ver o que a equipe tinha para fazer "To Do", o que estava sendo feito "Doing", o que estava pronto "Done" e o que havia sido aceito pelo PO, e portanto estava com issue fechada "Closed" além das abas "Testing", que está associada a histórias sendo testadas e "ERROR", que são para histórias com problemas.

![Kanban](http://i.imgur.com/0ivy8dt.png)

O quadro está divido nas seguintes trilhas:
* **Product Backlog**: Esta trilha é responsável por armazenar todas as histórias a serem realizadas no projeto.
* **Sprint Backlog**: Esta trilha contém as histórias selecionadas para realização na sprint atual.
* **In Progress**: Esta trilha contém as histórias da sprint atual que já começaram a ser realizadas.
* **Done**: Esta trilha contém as histórias da sprint atual que já foram concluídas.
* **Testing**: Esta trilha contém as histórias da sprint atual que estão sendo testadas.
* **ERROR**: Esta trilha contém as histórias com problemas.

O quadro está integrado ao repositório no Github e pode ser acessado por meio deste [link](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB#boards?repos=85082265).

----------------------------

**Observação**: O quadro é gerado pela ferramenta Zenhub. Para poder visualizar o quadro é necessário instalar  a extensão do Zenhub no navegador (esta extensão está disponível para os navegadores Google Chrome e Mozilla Firefox). Para instalar a extensão, deve-se seguir as seguintes etapas:
* Entre em [zenhub.com](https://zenhub.com)
* Clique em **Add Zenhub to Github**
* Após isso, vá à [página inicial do repositório](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB/) e será possível visualizar **Boards**, onde será possível ver o Kanban da equipe.