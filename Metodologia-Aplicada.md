## _Scrum_

### Papéis

<table class="tg">
  <tr>
    <th class="tg-30rh">Scrum Master</th>
    <th class="tg-5frq">Product Owner (PO)</th>
    <th class="tg-5frq">Development</th>
  </tr>
  <tr>
  </tr>
</table>

### Reuniões Diárias

#### Iteração 0

Nesse primeiro momento, foi seguida a metodologia proposta na disciplina, onde as reuniões são diárias. Na terça, quinta e sábado as reuniões serão presenciais, e nos demais dias, através do canal do slack "daily meetings".

### Reunião Semanal

Ao final de cada sprint a equipe se reunia para fazer a Sprint Review, Retrospectiva e o Planejamento da próxima sprint. Na Retrospectiva, a equipe conversava acerca dos pontos positivos, negativos e propostas de melhoria que deveriam ocorrer para melhor andamento do projeto. No planejamento, eram escritas as tasks de cada história pela equipe, os critérios de aceitação pelo PO e logo em seguida eram divididas entre o time de desenvolvimento.

### Artefatos

Dois artefatos foram produzidos e gerenciados pelo Product Owner: o Backlog do Produto, que contém todas as histórias derivadas, e o Backlog da Sprint, com as histórias planejadas para a sprint atual.

### Duração das Sprints

Conforme solicitado na disciplina, foram executadas sprints com duração de uma semana cada.

## Extreme programing (XP)

### Programação em Pares

Uma das práticas utilizadas no projeto foi o pareamento.

### Integração Contínua

Outra prática utilizada no projeto foi a integração contínua e deploy contínuo. A integração contínua era executada automaticamente sempre que uma mudança fosse realizada e colocada no repositório oficial do GitHub. Essa integração era realizada pela ferramenta CicleCI. 


## _Kanban_

Foi utilizado o Kanban para a equipe ter uma melhor visibilidade do projeto de forma que todos os integrantes do projeto possam visualizá-lo e modificá-lo de forma rápida e fácil, além de que qualquer pessoa interessada no projeto também possa visualizá-lo facilmente. Para facilitar esta visualização, foi usada a ferramenta ZenHub conectada ao Git. Na aba de Boards é possível ver o que a equipe tinha para fazer "To Do", o que estava sendo feito "Doing", o que estava pronto "Done" e o que havia sido aceito pelo PO, e portanto estava com issue fechada "Closed".

![](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2016.2-Time02-Jardim-Botanico-Mobile/imagens/kanban.png)

O quadro está divido nas seguintes trilhas:
* **Product Backlog**: Esta trilha é responsável por armazenar todas as histórias a serem realizadas no projeto.
* **Sprint Backlog**: Esta trilha contém as histórias selecionadas para realização na sprint atual.
* **In Progress**: Esta trilha contém as histórias da sprint atual que já começaram a ser realizadas.
* **Done**: Esta trilha contém as histórias da sprint atual que já foram concluídas.

O quadro está integrado ao repositório no Github e pode ser acessado por meio deste [link](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB#boards?repos=85082265).

----------------------------

**Observação**: O quadro é gerado pela ferramenta Zenhub. Para poder visualizar o quadro é necessário instalar  a extensão do Zenhub no navegador (esta extensão está disponível para os navegadores Google Chrome e Mozilla Firefox). Para instalar a extensão, deve-se seguir as seguintes etapas:
* Entre em [zenhub.com](https://zenhub.com)
* Clique em **Add Zenhub to Github**
* Após isso, vá à [página inicial do repositório](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB/) e será possível visualizar tanto as abas **Boards** quanto **Burndown**, onde será possível ver, respectivamente, o quadro Kanban e o burndown relativo a cada sprint.