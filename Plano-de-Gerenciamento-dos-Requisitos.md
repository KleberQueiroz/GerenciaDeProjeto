## Histórico de Revisões
| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|22/03/2017|1.0|Criando estutura do documento|Rafael Rabetti|
|23/03/2017|1.0|Introdução finalidade e gerenciamento |Rafael Rabetti|
|26/03/2017|1.01|Processo e gerência |Rafael Rabetti|
|26/03/2017|1.1|Rastreabilidade |Rafael Rabetti|
|27/03/2017|1.2|Matriz de Rastreabilidade |Rafael Rabetti|
|03/04/2017|2.0|Refatorando documento, criação de um outro documento para as tabelas de rastreabilidade |Rafael Rabetti|
|16/04/2017|2.1|Refatorando documento, introdução, processo de elicitação |Eduardo Brasil|
|16/04/2017|2.2|Gerenciamento dos requisitos, ferramentas para o gerenciamento e Programa de Gerenciamento de Requisitos|Eduardo Brasil|



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

### 1.1 Finalidade<a name="finalidade"></a>
Os requisitos são a base de todo e qualquer projeto. Este documento visa estabelecer o gerenciamento destes requisitos, mostrando todo o seu ciclo de vida dentro de um projeto, desde sua elicitação até a sua implementação. Definiremos aqui, o processo utilizado para elicitar os requisitos, a definição de prioridade e atributos dos requisitos e a sua rastreabilidade.

 ### 1.2 Visão Geral<a name="visaogeral"></a>
Neste documento é mostrado os papeis da equipe e do cliente dentro do projeto, assim como suas responsabilidades e ferramentas utilizadas para a elicitação e gerencia destes requisitos, afim de que se tenha uma visão completa sobre os requisitos existentes no projeto.

 ## 2. Gerenciamento de Requisitos
### 2.1 Organização e Responsabilidades<a name="organizacao"></a>

Neste tópico consta os papéis e responsabilidades que tangem os envolvidos no projeto quanto as atribuições de cada um destes. 

* Equipe de gerência do projeto(GPP): Responsável pela a elicitação dos requisitos junto ao cliente e documentar os mesmo e sempre manterem os requisitos atualizados afim de que se haja alguma mudança nestes eles sejam atualizados nos documentos referentes ao projeto.

* Equipe de desenvolvimento de software(MDS): Responsável por documentar estes requisitos e mante los no documento de visão juntamente com o desenvolvimento da arquitetura bem como o diagrama de casos de e a descrição do mesmo.

* Cliente(CPD UnB): Responsável por participar das reuniões de elicitação e validação bem como disponibilizar os insumos  para o desenvolvimento do projeto de forma que a validação seja correspondente com a sua expectativa.
  

## 2. Processo de elicitação dos requisitos

#### 2.2.1 Ferramentas de elicitação<a name="elicitacao"></a>
Para a elicitação dos requisitos optou-se pelas seguintes ferramentas:

* **Entrevista:** Considerando o fato de que o cliente está geograficamente distante das equipes de gerência e desenvolvimento, será aplicada a técnica de entrevista com o objetivo de se ter uma noção inicial do projeto. Neste caso a entrevista terá um aspecto mais informal, com um tom de conversa, para entendimento do domínio da aplicação e do problema e assim identifição inicial dos requisitos.

* **Brainstorm:** Com as informações obtidas na entrevista com o cliente, será apresentado para a equipe essa visão do problema e do domínio. Com essa visão será feito um brainstorming para que o time obtenha pontos de vista  a fim de levantar os requisitos necessários. Depois de todos darem a sua opinião será feita a análise e negociação desses requisitos.

* **Questionário:** O questionário será usado para validar com os futuros usuários da aplicação se a solução proposta está de acordo com as suas necessidades.

* **Prototipação:** Criação de  protótipos de telas contendo as possíveis entradas e saídas do sistema. Assim, o usuário tem uma maior compreensão de como os requisitos serão aplicados dentro do sistema. 

### Justificativas:

As técnicas selecionadas não necessitam de uma aproximação constante do cliente ao processo e não requerem grande disponibilidade das equipes para que a interação aconteça.  Além disso, as técnicas vão de acordo com o processo de desenvolvimento adotado.

#### 2.2.2 Ferramentas para gerenciamento<a name="gerenciamento"></a>
Para gerenciar os requisitos durante a release 1 foram utilizadas as ferramentas:

* Gmail Contato inicial com o cliente e solução rápida de duvidas. 

* Google drive Utilizado para criação da documentação inicial dos requisitos elicitados.

* Wiki do Github Utilizado para a documentação oficial do projeto, baseada em versionamento, para visibilidade dos envolvidos e repositório oficial dos requisitos documentados assim como a manutenção destes requisitos em caso de mudanças. 

### 3. O Programa de Gerenciamento de Requisitos
#### 3.1 Identificação de Requisitos<a name="identificacao"></a>	 	 	
##### 3.1.1 Descrição do Problema<a name="problema"></a>

| ID | O problema de | afeta | cujo impacto é | Uma boa solução seria |
|----|---------------|-------|----------------|-----------------------|
| P1 | A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro,  | estudantes, servidores e visitantes da universidade | a demora para encontrar e chegar à determinado lugar na universidade |  uma plataforma web que fornece as informações de localização de salas e prédios dentro do campus. |

##### 3.1.2 Identificação das Necessidades<a name="necessidades"></a>

| ID | Necessidade | Prioridade | Preocupações | Solução Atual | Soluções Propostas |
|----|-------------|------------|--------------|---------------|--------------------|
| P1NE1 | Mostrar a Localização e informaçoes de Prédios e departamentos | Alta | Cliente não ter os dados referentes aos prédios, departamentos ou salas | Google Maps. | Utilizar dados obtidos para manter a localização de predios, departamentos e afins. |
| P1NE2 | Informações a respeito das instalações da UnB assim como melhores rotas | Alta | Informações desatualizadas na base de dados do CPD | Google Maps | Utilizar dados obtidos para manter a localização dos departamentos. |

##### 3.1.3 Definição das características<a name="caracateristicas"></a>

| ID | Características |
|----|-----------------|
| NE1CA1  |


#####3.1.4 Definição dos casos de uso<a name="casosdeuso"></a>

| ID | Casos de uso |
|----|-----------------|
|  |  |
	

## 4. Gerenciamento da priorização e atributos de requisitos

A priorização dos requisitos se deu por meio da experiência da equipe de gerência em identificar quais os requisitos são mais facilmente implementados, mas mais importante que isso, quais requisitos implementam a arquitetura estabelecida para o software.

* Atributos

   * Valor agregado

   * Impacto na arquitetura

   * Risco

   * Esforço 

## 5. Gerência de Requisitos

###  Rastreabilidade

A rastreabilidade se dará pela seguinte classificação de níveis: Problema, Necessidades, Características, Requisitos Funcionais e Não-Funcionais e Casos de uso. De acordo com esses níveis de rastreabilidade, o nível de impacto do projeto caso haja alguma mudança em algum, segue a mesma lógica. Sendo o maior impacto se houver mudança no Problema e o menor impacto se houver mudança no Caso de Uso.

  
#### 5.1 Problemas

Os problemas são o nível mais altos de requisitos, desses problemas são demandadas soluções de *software*. Todo problema deve conter:

* **Índice**: Iniciado com a letra 'P' seguido de um número crescente de acordo com a quantidade de problemas.

* **Nome**: Nome do problema identificado.

* **Descrição**: Detalhamento do problema a ser solucionado.

#### 5.2 Necessidades

As necessidades são uma abstração dos problemas e a resolução dessas necessidades impactam na resolução do problema associado.

* **Índice**: Iniciado com as letras 'NE' seguido de um número crescente de acordo com a quantidade de necessidades.

* **Nome**: Nome da necessidade identificada.

* **Descrição**: Detalhamento da necessidade.

#### 5.3 Características

São características do sistema que buscam atender a uma necessidade específica.

* **Índice**: Iniciado com as letras 'CA' seguido de um número crescente de acordo com a quantidade de características.

* **Nome**: Nome da característica identificada.

* **Descrição**: Detalhamento da característica.

#### 5.4 Requisitos

São propriedades e comportamentos que o produto de *software* deve atender.

* **Índice**: Iniciado com a letra 'R' seguido de um número crescente de acordo com a quantidade de requisitos.

* **Nome**: Nome do requisito identificado.

* **Descrição**: Detalhamento do requisito.

#### 5.5 Casos de Uso

São unidades funcionais do sistema. Representam a interação entre o usuário e o sistema.

* **Índice**: Iniciado com as letras 'UC' seguido de um número crescente de acordo com a quantidade de casos de uso.

* **Nome**: Nome do caso de uso identificado.

* **Descrição**: Detalhamento do caso de uso.

