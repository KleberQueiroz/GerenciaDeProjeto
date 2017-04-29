## Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|28/04/2017|0.1|Criação do documento voltado a R2|Alexandre Torres Kryonidis|
***

## Sumário

[1. Introdução](#1-introducao)  

[2. Processo de Qualidade](#2-Processo-de-Qualidade)

[3. GQM do Projeto](#3-GQM-do-Projeto)

[4. Ferramentas da análise de qualidade](#3-Ferramentas-da-análise-de-qualidade)

[5. Referências Bibliográficas](#5-Referências-Bibliograficas)

## 1. Introdução

<p align="justify">O gerenciamento de qualidade é uma coleção de processos que garantem a qualidade em relação ao ciclo de vida, produto de software e serviços também de acordo com as necessidades dos stakeholders (PMBoK, 2014).
Este documento tem como finalidade descrever questões de planejamento, garantia e controle da qualidade do Onde é UnB.

## 2. Processo de Qualidade

<p align="justify">O processo de qualidade será dado a partir de uma sequência de passos definidos no PMBoK. As fases do processo de qualidade serão dados nas etapas de Planejamento, Execução e Monitoramento e Controle do projeto.

[![Captura de tela de 2017-04-19 00-33-08.png](https://s10.postimg.org/6xnfo9pkp/Captura_de_tela_de_2017-04-19_00-33-08.png)](https://postimg.org/image/7zxm6t8dx/)

* <p align="justify">Criar o planejamento da gerencia de qualidade: consiste na elaboração de um plano que contem a identificação dos requisitos ou padrões de qualidade do projeto. Realizar esse processo auxilia no fornecimento de orientações e instruções sobre como será validada e gerenciada a qualidade do projeto. 

* <p align="justify">Garantir a qualidade: é o processo para garantir o uso de padrões de qualidade, de auditoria dos requisitos de qualidade e resultados de medição.

* <p align="justify"> Monitorar e controlar a qualidade do projeto: é dado ao monitorar, registrar para então avaliar o desempenho e recomendar mudanças no projeto. É benéfico ao projeto pois identifica causas da baixa qualidade e pode fazer recomendações para elimina-la e valida a conformidade do projeto para com as partes interessadas.

## 3. GQM do projeto

<p align="justify">O Goal Question Metric (GQM), é um paradigma de medição que visa definir e integrar objetivos à modelos de processo, produto e aspectos de qualidade. É uma abordagem orientada a metas que tem como base a definição de metas operacionais e mensuráveis top-down no processo de medição e interpretação dos dados resultantes bottom-up. O processo GQM é separado em passos ou fases que cobrem todo o planejamento e execução de um plano de medições.

### 3.1. Objetivos

<p align="justify">O objetivo do projeto trata do seu ponto de vista, o propósito e o ambiente (SARAIVA, 2006). Com isso a seguinte tabela busca representar os objetivos de qualidade do OndeÉ?UnB.

| Dimensão | Objetivo|
|-----------------------|---------------------|
| Analisar | Código |
| Com propósito de | Conhecer e Melhorar|
| Com respeito a | Qualidade |
| Sob ponto de vista do | Desenvolvedor |
| No contexto de | Projeto OndeÉ?UnB |

### 3.2. Perguntas

<p align="justify">Perguntas ou Questões são definidas a partir dos objetivos estabelecidos para obter informações sobre os mesmos. Para cada fator de qualidade registrado no Abstraction Sheet é gerada uma mais perguntas que nada mais serão do que um resultados para o objetivo de mensuração.


* Qual a qualidade do código do OndeÉUnB?

<p align="justify">O nível de qualidade do código será dado a partir de três fatores: Complexidade, Tamanho da Classe, Cobertura de Testes.

| <p align="left">Fatores de Qualidade | <p align="left">Fatores de Variação |
|-------------------------------------------|------------------------------------------------------------------------|
| Complexidade do código<br/>Taxa de comentários<br/>Cobertura de Testes | Experiência do desenvolvedor com a linguagem<br/>Motivação do Desenvolvedor |
| **Hipótese de Linha-Base** | **Impacto na Hipótese de Linha-Base** |
| Espera se que o projeto tenha complexidade 5<br/>É esperado que na R1 tenha mais de 30% de cobertura de testes e na R2 mais de 90%<br/>A classe tem um número de linhas <= 100<br/>O código possui uma pontuação de 15 no ABC metric|Com o impacto dos fatores de variação, prevê-se que a complexidade do código seja 8<br/>Que a cobertura de testes diminua 10% em relação a Hipótese de Linha-Base <br/>O código irá possui 150 linhas por classe<br/>O codigo tem nota 20 em relação ao ABC metric|

### 3.3. Métricas

#### M1. Complexidade

<p align="justify">Segundo uma pesquisa sobre psicologia cognitiva, um indivíduo consegue armazenar em sua memória de 5 a 9 objetos simultaneamente (MOURÃO, 2015). Por isso, um desenvolvedor ao analisar o código e necessitar dar uma manutenção ao mesmo teria uma dificuldade maior em assimilar 6 caminhos diferentes ou mais, o ideal seria que no máximo o código tivesse 5 caminhos, por isso foi escolhida a complexidade média foi de  5.

| M1 | Complexidade |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Complexidade de código |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso seja alta a complexidade, o código deverá ser refatorado. |
| Meta | A complexidade será considerada: Baixa < 5, Regular = 5, Alta > 5. |
|Ferramenta| Code Climate/Rubocop|

#### M2. Cobertura de Testes

<p align="justify">A cobertura de testes possui um caráter de analisar dinamicamente o produto. É uma atividade para a identificação e eliminação de erros que possam persistir. O conjunto de informações obtidas a partir dos testes de software tem grande valor para atividades como a manutenção, depuração e estimativa de confiabilidade de software (MALDONADO, 2007).

| M2 | Cobertura de Testes |
|-------------------|----------------------------------------------------------------------------------------|
| Medida | Funcionalidades/Total de Funcionalidades |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso metas não sejam atingidas, buscar entender motivos e e tomar decisões corretivas. |
| Meta | Testes R1 > 30%, Testes R1 > 90% |
|Ferramenta|SimpleCov, Cucumber, rspec|

#### M3. Tamanho de Classes

<p align="justify">Com o objetivo de manter uma boa modularização do código, será calculado a quantidade de linhas de cada classe.

| M3 | Tamanho da Classe |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Linhas por classe |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso seja ultrapassada a meta, o código deverá ser refatorado. |
| Meta | Cada classe deve ter no máximo 100 linhas de código |
|Ferramenta| Code Climate/Rubocop|


#### M4. Linhas por método

<p align="justify">Devido a alta distinção entre métodos, cada um tendo sua função específica. Esta métrica será utilizado apenas para fins informativos e possivelmente para refatoração.

| M4 | Linhas por Método - ABC Metric |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Pontuação Linhas por Método |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Se o limite for ultrapassado, refatorar método. |
| Meta | Pontuação de 15 ou menor que 15. |
|Ferramenta| Code Climate/Rubocop|

## 4. Ferramentas para análise de qualidade

### 4.1. Code Climate

<p align="justify">Code Climate é uma ferramenta de análise estática que coleta diversas métricas. Nela podem ser configuradas diversas ferramentas, dentre elas o Rubocop.

### 4.2. Rubocop

<p align="justify">Rubocop é uma das ferramentas que o Code Climate utiliza, tendo grande importância para o OndeEUnB pois fará a maior parte das coletas de métricas.

### 4.3. CircleCI

<p align="justify">Circle CI é uma ferramenta de integração contínua e deploy para projetos hospedados no GitHub. Nele é possível criar uma build em cada commit, passando por todos os testes unitários e de integração. Garantindo assim que a versão no servidor será sempre a última versão estável do software.

### 4.4. SimpleCov

<p align="justify">O SimpleCov é uma ferramenta de análise para ruby on rails, ele determina o status de cobertura de testes para cada arquivo do seu projeto.

### 4.5. Cucumber

<p align="justify">Cucumber é uma ferramentar em que é possível escrever testes de aceitação automatizados do sistemas. No Cucumber são executados passos que descrevem como o software deve se comportar.

### 4.6. RSpec

RSpec é uma ferramenta de testes para Rails de testes unitários. Ela fornece uma forma de encapsular o que irá ser testado com um bloco "describe".

## 5. Referências Bibliográficas

<p align="justify">PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.

<p align="justify">MOURAO JUNIOR, Carlos Alberto  and  FARIA, Nicole Costa. Memória. Psicol. Reflex. Crit. [online]. 2015, vol.28, n.4, pp.780-788. Available from: <http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0102-79722015000400017&lng=en&nrm=iso>. ISSN 0102-7972.  http://dx.doi.org/10.1590/1678-7153.201528416.

<p align="justify">SARAIVA, V. A. 2006. "UTILIZAÇÃO DA ABORDAGEM GOAL-QUESTION-METRICS (GQM) NA ELABORAÇÃO E EXECUÇÃO DE PLANOS DE AVALIAÇÃO DE USABILIDADE DE SOFTWARE : UM ESTUDO EMPÍRICO SOBRE UM SOFTWARE AGROPECUÁRIO".

<p align="justify">MALDONADO, José Carlos et al. Introduçao ao teste de software. Rio de Janeiro: Campus, 2007.
