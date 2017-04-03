## Histórico de Revisões
| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|22/03/2017|1.0|Criando estutura do documento|Rafael Rabetti|
|23/03/2017|1.0|Introdução e gerenciamento |Rafael Rabetti|
|26/03/2017|1.01|Processo e gerência |Rafael Rabetti|
|26/03/2017|1.1|Rastreabilidade |Rafael Rabetti|
|27/03/2017|1.2|Matriz de Rastreabilidade |Rafael Rabetti|
|03/04/2017|2.0|Refatorando documento, criação de um outro documento para as tabelas de rastreabilidade |Rafael Rabetti|



***
## Sumário

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

A rastreabilidade se dará pela seguinte classificação de níveis: Problema, Necessidades, Características, Requisitos Funcionais e Não-Funcionais e Casos de uso. De acordo com esses níveis de rastreabilidade, o nível de impacto do projeto caso haja alguma mudança em algum, segue a mesma lógica. Sendo o maior impacto se houver mudança no Problema e o menor impacto se houver mudança no Caso de Uso.

  
#### 4.1 Problemas

Os problemas são o nível mais altos de requisitos, desses problemas são demandadas soluções de *software*. Todo problema deve conter:

* **Índice**: Iniciado com a letra 'P' seguido de um número crescente de acordo com a quantidade de problemas.

* **Nome**: Nome do problema identificado.

* **Descrição**: Detalhamento do problema a ser solucionado.

#### 4.2 Necessidades

As necessidades são uma abstração dos problemas e a resolução dessas necessidades impactam na resolução do problema associado.

* **Índice**: Iniciado com as letras 'NE' seguido de um número crescente de acordo com a quantidade de necessidades.

* **Nome**: Nome da necessidade identificada.

* **Descrição**: Detalhamento da necessidade.

#### 4.3 Características

São características do sistema que buscam atender a uma necessidade específica.

* **Índice**: Iniciado com as letras 'CA' seguido de um número crescente de acordo com a quantidade de características.

* **Nome**: Nome da característica identificada.

* **Descrição**: Detalhamento da característica.

#### 4.4 Requisitos

São propriedades e comportamentos que o produto de *software* deve atender.

* **Índice**: Iniciado com a letra 'R' seguido de um número crescente de acordo com a quantidade de requisitos.

* **Nome**: Nome do requisito identificado.

* **Descrição**: Detalhamento do requisito.

#### 4.5 Casos de Uso

São unidades funcionais do sistema. Representam a interação entre o usuário e o sistema.

* **Índice**: Iniciado com as letras 'UC' seguido de um número crescente de acordo com a quantidade de casos de uso.

* **Nome**: Nome do caso de uso identificad.

* **Descrição**: Detalhamento do caso de uso.

