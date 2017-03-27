## Histórico de Revisões
| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|22/03/2017|1.0|Criando estutura do documento|Rafael Rabetti|
|23/03/2017|1.0|Introdução e gerenciamento |Rafael Rabetti|
|26/03/2017|1.0|Processo e gerência |Rafael Rabetti|
|26/03/2017|1.1|Rastreabilidade |Rafael Rabetti|


***

1. [Introdução](#1-introdução)

2. [Processo de elicitação dos requisitos](#2-processo-de-elicitação-dos-requisitos)

3. [Gerenciamento da priorização e atributos de requisitos](#3-gerenciamento-da-priorização-e-atributos-de-requisitos)

4. [Rastreabilidade](#4-rastreabilidade)

## 1. Introdução

Os requisitos são a base de todo e qualquer projeto. Este documento visa estabelecer o gerenciamento destes requisitos, mostrando todo o seu ciclo de vida dentro de um projeto, desde sua elicitação até a sua implementação. Definiremos aqui, o processo utilizado para elicitar os requisitos, a definição de prioridade e atributos dos requisitos e a sua rastreabilidade.

## 2. Processo de elicitação dos requisitos

* **Entrevista com Cliente**

 Considerando o fato de que o cliente está geograficamente distante das equipes de gerência e desenvolvimento, será aplicada a técnica de entrevista com o objetivo de se ter uma noção inicial do projeto. Neste caso a entrevista terá um aspecto mais informal, com um tom de conversa, para entendimento do domínio da aplicação e do problema e assim identifição inicial dos requisitos.

* **Brainstorming entre a equipe**

 Com as informações obtidas na entrevista com o cliente, será apresentado para a equipe essa visão do problema e do domínio. Com essa visão será feito um *brainstorming* a fim de levantar os requisitos. Depois de todos darem a sua opinião será feita a análise e negociação desses requisitos.
 
* **Questionário**

 O questionário será usado para validar com os futuros usuários da aplicação se a solução proposta está de acordo com as suas necessidades.

* **Prototipação**

 Criação de  protótipos de telas contendo as possíveis entradas e saídas do sistema. Assim, o usuário tem uma maior compreensão de como os requisitos serão aplicados dentro do sistema. 

##### Justificativas:

As técnicas selecionadas não necessitam de uma aproximação constante do cliente ao processo e não requerem grande disponibilidade das equipes para que a interação aconteça.  Além disso, as técnicas vão de acordo com o processo de desenvolvimento adotado.

## 3. Gerenciamento da priorização e atributos de requisitos

A priorização dos requisitos se deu por meio da experiência da equipe de gerência em identificar quais os requisitos são mais facilmente implementados, mas mais importante que isso, quais requisitos implementam a arquitetura estabelecida para o software.

* Atributos

   * Valor agregado

   * Impacto na arquitetura

   * Risco

   * Esforço 

## 4. Gerência de Requisitos

###  Rastreabilidade

A rastreabilidade se dará pela seguinte classificação de níveis: Problema, Necessidades, Características, Requisitos Funcionais e Não-Funcionais e Casos de uso. De acordo com esses níveis de rastreabilidade, o nível de impacto do projeto caso haja alguma mudança em algum, segue a mesma lógica. Sendo o maior impacto se houver mudança no Problema e o menor impacto se houver mudança no Caso de Uso. Os índices iniciados com a letra 'P' são problemas, com as letras 'NE' são necessidades, com as letras 'CA' são características, com a letra 'R' são requisitos e com as letras 'UC' são casos de uso.
  
#### 4.1 Problema

| **ID**   | **Problema**     | **Descrição**|
|----------|-----------------|---------------|
| **P01** | Dificuldade de localização |A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro afeta estudantes, servidores e visitantes da universidade, cujo impacto é a demora para encontrar e chegar à determinado lugar na universidade, causando atrasos.|

#### 4.2 Necessidades
| **ID**   | **Problema**     | **Descrição**|
|----------|-----------------|---------------|
|**NE01**|Localização de Prédios|A falta de sinalização e o grande número e espaçamento dos prédios dificulta a localização dos mesmos.|
|**NE02**|Localização de Departamentos|A falta de sinalização e o grande número de departamentos nos vários prédios dificultam a sua localização.|
|**NE03**|Localização de Salas de Aula|Os alunos sentem a necessidade de saber onde ficam as suas salas de aula, assim não precisam ficar perdendo tempo procurando.|
|**NE04**|Localização de Salas de Professores|Os alunos sentem a necessidade de saber onde fica a sala de tal professor com mais facilidade, em vez de toda vez que precisarem, perguntar ao professor.|
|**NE05**|Localização de Laboratórios|Muitos alunos e professores contribuem para a universidade com pesquisa científica e por isso é fundamental saber a localização dos laboratórios.|
|**NE06**|Localização de locais de alimentação|Saber a localização do RU ou de alguma outra lanchonete é fundalmental para os alunos.|
|**NE07**|Localização de centros acadêmicos|Para fazer novas amizades e conhecer gente nova, é essencial saber onde ficam os centros acadêmicos.|
|**NE08**|Indicar trajetos entre locais|Além de saber onde fica, é importante saber como chegar.|

#### 4.3 Características
