## Histórico de Revisões
| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|22/03/2017|1.0|Criando estutura do documento|Rafael Rabetti|
|23/03/2017|1.0|Introdução e gerenciamento |Rafael Rabetti|
|26/03/2017|1.01|Processo e gerência |Rafael Rabetti|
|26/03/2017|1.1|Rastreabilidade |Rafael Rabetti|
|27/03/2017|1.2|Matriz de Rastreabilidade |Rafael Rabetti|


***

1. [Introdução](#1-introdução)

2. [Processo de elicitação dos requisitos](#2-processo-de-elicitação-dos-requisitos)

3. [Gerenciamento da priorização e atributos de requisitos](#3-gerenciamento-da-priorização-e-atributos-de-requisitos)

4. [Gerência de requisitos](#4-gerência-de-requisitos)

    4.1 [Problemas](#41-problemas)

    4.2 [Necessidades](#42-necessidades)

    4.3 [Características](#43-características)

    4.4 [Requisitos](#44-requisitos)

    4.5 [Casos de uso](#45-casos-de-uso)

    4.6 [Matriz de rastreabilidade](#46-matriz-de-rastreabilidade)

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

  
#### 4.1 Problemas

| **ID**   | **Problema**     | **Descrição**|
|----------|-----------------|---------------|
| **P01** | Dificuldade de localização |A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro afeta estudantes, servidores e visitantes da universidade, cujo impacto é a demora para encontrar e chegar à determinado lugar na universidade, causando atrasos.|

#### 4.2 Necessidades

| **ID**   | **Necessidade**     | **Descrição**|
|----------|-----------------|---------------|
|**NE01**|Orienteção dentro do campus|Atualmente, a localização dentro do campus conta apenas com marcações de teto que muitas vezes são de difícil visualização.|

#### 4.3 Características

| **ID**   | **Característica**     | **Descrição**|
|----------|-----------------|---------------|
|**CA01**|Mapa com as principais localidades.| Apresentação da localização de salas e edifícios.|
|**CA02**|Orientação entre localidades| Apresentação de rotas e caminhos entre as principais localidades. |

#### 4.4 Requisitos
| **ID**   | **Requisito**     | **Descrição**|
|----------|-----------------|---------------|
|**R01**|Localizar Edifícios|O sistema deve apresentar ao usuário a localização dos vários edifícios dentro do campus.|
|**R02**|Localizar Departamentos|O sistema deve apresentar ao usuário a localização dos vários departamentos dentro do campus.|
|**R03**|Localizar Salas|O sistema deve apresentar ao usuário a localização das salas dentro do campus.|
|**R04**|Localizar locais de alimentação|O sistema deve apresentar ao usuário a localização dos locais de alimentação dentro do campus.|
|**R05**|Localizar centros acadêmicos|O sistema deve apresentar ao usuário a localização dos centros acadêmicos dentro do campus.|
|**R06**|Indicar trajetos entre locais|O sistema deve apresentar rotas, partindo da localização atual do usuário até o destino desejado.|

#### 4.5 Casos de Uso

| **ID**   | **Caso de Uso**     | **Descrição**|
|----------|-----------------|---------------|
|**UC01**|Manter Edifícios|Permite a criação, leitura, exclusão e alteração de edifícios.|
|**UC02**|Manter Salas|Permite a criação, leitura, exclusão e alteração de salas.|
|**UC03**|Manter Departamentos|Permite a criação, leitura, exclusão e alteração de departamentos.|
|**UC04**|Manter Centros Acadêmicos|Permite a criação, leitura, exclusão e alteração de centros acadêmicos.|
|**UC05**|Visualizar Informações Sobre Edifício|Apresenta para o usuário qual o nome do edifício e quais departamentos e salas estão ali dentro. |
|**UC06**|Pesquisar Edifícios|Permite ao usuário a busca um edifício a fim de saber a sua localização.|
|**UC07**|Pesquisar Sala|Permite ao usuário a busca uma sala a fim de saber a sua localização.|
|**UC08**|Pesquisar Departamento|Permite ao usuário a busca um departamento a fim de saber a sua localização.|
|**UC09**|Visualizar Centros Acadêmicos|Apresenta ao usuário a localização dos centros acadêmicos dentro do campus.|
|**UC10**|Visualizar Locais de Alimentação|Apresenta ao usuário a localização dos locais de alimentação dentro do campus.|
|**UC11**|Traçar rotas|Permite ao usuário, partindo da sua localização atual, traçar rotas para chegar a um destino desejado.|

#### 4.6 Matriz de rastreabilidade

![Imgur](http://i.imgur.com/CVCbacj.png)

[Clique aqui para visualizar melhor](http://i.imgur.com/CVCbacj.png)