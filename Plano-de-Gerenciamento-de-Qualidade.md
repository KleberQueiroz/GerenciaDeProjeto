# Plano de Gerenciamento dos Riscos

## Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|02/04/2017|0.1|Criação do documento|Eduardo Gomes|
|04/04/2017|0.2|Adição de Introdução e Processo de Qualidade|Eduardo Gomes|
|04/04/2017|0.3|Métricas e Ferramentas|Matheus Mello|
|19/04/2017|1.0|Adição do GQM|Eduardo Gomes|

***

## Sumário

[1. Introdução](#1-introducao)  

[2. Processo de Qualidade](#2-Processo-de-Qualidade)

[3. Ferramentas da análise de qualidade](#3-Ferramentas-da-análise-de-qualidade)

[4. Métricas](#4-Metricas)

[5. Referências Bibliográficas](#5-Referências-Bibliograficas)

## 1. Introdução

O gerenciamento de qualidade é uma coleção de processos que garantem a qualidade em relação ao ciclo de vida, produto de software e serviços também de acordo com as necessidades dos stakeholders (PMBoK, 2014).
Este documento tem como finalidade descrever questões de planejamento, garantia e controle da qualidade do Onde é UnB.

## 2. Processo de Qualidade

<p align="justify">O processo de qualidade será dado a partir de uma sequência de passos definidos no PMBoK. As fases do processo de qualidade serão dados nas etapas de Planejamento, Execução e Monitoramento e Controle do projeto.

[![Captura de tela de 2017-04-19 00-33-08.png](https://s10.postimg.org/6xnfo9pkp/Captura_de_tela_de_2017-04-19_00-33-08.png)](https://postimg.org/image/7zxm6t8dx/)

* <p align="justify">Criar o planejamento da gerencia de qualidade: consiste na elaboração de um plano que contem a identificação dos requisitos ou padrões de qualidade do projeto. Realizar esse processo auxilia no fornecimento de orientações e instruções sobre como será validada e gerenciada a qualidade do projeto. 

* <p align="justify">Garantir a qualidade: é o processo para garantir o uso de padrões de qualidade, de auditoria dos requisitos de qualidade e resultados de medição.

* <p align="justify">Monitorar e controlar a qualidade do projeto: é dado ao monitorar, registrar para então avaliar o desempenho e recomendar mudanças no projeto. É benéfico ao projeto pois identifica causas da baixa qualidade e pode fazer recomendações para elimina-la e valida a conformidade do projeto para com as partes interessadas.

## 2. GQM do projeto

<p align="justify">O Goal Question Metric (GQM), é um paradigma de medição que visa definir e integrar objetivos à modelos de processo, produto e aspectos de qualidade. É uma abordagem orientada a metas que tem como base a definição de metas operacionais e mensuráveis top-down no processo de medição e interpretação dos dados resultantes bottom-up. O processo GQM é separado em passos ou fases que cobrem todo o planejamento e execução de um plano de medições.

### 2.1. Objetivos

<p align="justify">O objetivo do projeto trata do seu ponto de vista, o propósito e o ambiente (SARAIVA, 2006). Com isso a seguinte tabela busca representar os objetivos de qualidade do OndeÉ?UnB.

| Dimensão | Objetivo|
|-----------------------|---------------------|
| Analisar | Código |
| Com propósito de | Conhecer e Melhorar|
| Com respeito a | Qualidade |
| Sob ponto de vista do | Desenvolvedor |
| No contexto de | Projeto OndeÉ?UnB |

### 2.2. Perguntas

<p align="justify">Perguntas ou Questões são definidas a partir dos objetivos estabelecidos para obter informações sobre os mesmos. Para cada fator de qualidade registrado no Abstraction Sheet é gerada uma mais perguntas que nada mais serão do que um resultados para o objetivo de mensuração.


| <p align="left">Fatores de Qualidade | <p align="left">Fatores de Variação |
|-------------------------------------------|------------------------------------------------------------------------|
| Complexidade do código<br/>Taxa de comentários<br/>Cobertura de Testes | Experiência do desenvolvedor com a linguagem<br/>Motivação do Desenvolvedor |
| **Hipótese de Linha-Base** | **Impacto na Hipótese de Linha-Base** |
| Espera se que o projeto tenha complexidade 5<br/>É esperado que tenha uma linha de comentário a cada dez linhas de código<br/>É esperado que na R1 tenha mais de 30% de cobertura de testes e na R2 mais de 90%<br/>A classe tem um número de linhas <= 100|Com o impacto dos fatores de variação, prevê-se que a complexidade do código seja 8<br/>O código tenha 1 linha de comentário a cada 15<br/>Que a cobertura de testes diminua 10% em relação a Hipótese de Linha-Base <br/>O código irá possui 150 linhas por classe |

### 2.3. Métricas

#### M1. Complexidade

<p align="justify">Segundo uma pesquisa sobre psicologia cognitiva, um indivíduo consegue armazenar em sua memória de 5 a 9 objetos simultaneamente (MOURÃO, 2015). Por isso, um desenvolvedor ao analisar o código e necessitar dar uma manutenção ao mesmo teria uma dificuldade maior em assimilar 6 caminhos diferentes ou mais, o ideal seria que no máximo o código tivesse 5 caminhos, por isso foi escolhida a complexidade média foi de  5.

| M1 | Complexidade |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Complexidade de código |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso seja alta a complexidade, o código deverá ser refatorado. |
| Meta | A complexidade será considerada: Baixa < 5, Regular = 5, Alta > 5. |
|Ferramenta| Codacy/Rubocop|

#### M2. Taxa de Comentários

#### M3. Cobertura de Testes



#### M4. Tamanho de Classes

<p align="justify">Com o objetivo de manter uma boa modularização do código, será calculado a quantidade de linhas de cada classe.

| M4 | Tamanho da Classe |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Linhas por classe |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso seja ultrapassada a meta, o código deverá ser refatorado. |
| Meta | Cada classe deve ter no máximo 100 linhas de código |
|Ferramenta| Codacy/Rubocop|




* **Desenvolvimento do Plano GQM**

<p align="justify">Baseado nos objetivos, foi desenvolvido um plano GQM que consiste em objetivo, perguntas e métricas.

<p align="justify">

| <p align="left">Fatores de Qualidade | <p align="left">Fatores de Variação |
|-------------------------------------------|------------------------------------------------------------------------|
| Complexidade do código<br/>Taxa de comentários | Experiência do desenvolvedor com a linguagem<br/>Motivação do Desenvolvedor |
| **Hipótese de Linha-Base** | **Impacto na Hipótese de Linha-Base** |
| Deve haver complexidade de no máximo 5<br/>Deve haver no mínimo uma linha de comentário a cada quatro linhas de código<br/>Duplicidade de código|  |

* **Perguntas e Métricas**

**Pergunta 1:** Qual a qualidade do código do OndeÉUnB?

<p align="justify">O nível de qualidade do código será dado a partir de três fatores: Complexidade, Quantidade de Comentários por Quantidade de Linhas e Duplicidade de Código. Para cada variável será atribuída uma pontuação. Os quadros a seguir contém os critérios para julgar a qualidade em cada variável. A partir dos resultados obtidos, essas variáveis poderão interpoladas para se ter uma conclusão final sobre a qualidade do código.

**Métrica 1:** Complexidade do Código

<p align="justify">Segundo uma pesquisa sobre psicologia cognitiva, um indivíduo consegue armazenar em sua memória de 5 a 9 objetos simultaneamente (MOURÃO, 2015). Por isso, um desenvolvedor ao analisar o código e necessitar dar uma manutenção ao mesmo teria uma dificuldade maior em assimilar 6 caminhos diferentes ou mais, o ideal seria que no máximo o código tivesse 5 caminhos, por isso foi escolhida a complexidade média foi de  5.

| Qualidade relacionada a Complexidade | Média de Complexidade do Código |
|--------------------------------------|---------------------------------|
| Baixa | Complexidade < 5 |
| Média | Complexidade = 5 |
| Alta | Complexidade > 5 |

**Métrica 2:** Comentários por Total de Linhas

<p align="justify">Dentre o número de aplicações de técnicas de comentários, será definido o número de uma linha de comentário para cada dez linhas de código.

| Qualidade relacionada a Comentários | Linhas de Comentários / Quantidade total de linhas (C) |
|-------------------------------------|--------------------------------------------------------|
| Baixa | C < 1/10 |
| Média | C = 1/10 |
| Alta | C > 1/10 |

**Métrica 3:** Código Duplicado

<p align="justify">A ideologia Don't Repeat Yourself (DRY) é um conceito de programação que defende que um sistema deve possuir uma representação única. A não repetição de código auxilia a tornar o código manutenível.

| Qualidade para Código Duplicado | Possui |
|---------------------------------|--------|
| Baixa | Sim |
| Alta | Não |


**Métrica 4:** Cobertura de Teste

|              **Indicador**                |            **Legenda**              |
|:-------------------------------:|:---------------------------:|
|acima de 90%   |Excelente|
|50% - 89%   |Bom|
|30% - 49%   |Razoável|
|abaixo de 30%   |Ruim|

**Métrica 5:** Número de Caracteres por Linha

De acordo com o guia de estilo, cada linha deverá ter no máximo 80 caracteres.

**Métrica 6:** Número de Linhas por Método

Devido a alta distinção entre métodos, cada um tendo sua função específica. Esta métrica será utilizado apenas para fins informativos, para a averiguação dos resultados será utilizada a Complexidade Ciclomática, tendo como foco um bom design de operações.

## 3. Ferramentas para análise de qualidade

### Flay

É uma ferramenta que procura por duplicações de código.

### Saikuro

Saikuro é um analisados de complexidade ciclomática para Ryby, gera um relatório com a complexidade ciclomática de cada método encontrado, Sakuro ainda conta o número de linhas por método e ainda pode gerar uma lista com o número de caracteres por linha de código.

### Churn

Com Churn é possível ter o controle da quantidade de vezes que um arquivo, classe ou método é alterado durante o ciclo de vida de um projeto

### Rails Best Practices

Rails Best Practices é uma ferramenta de métricas que checa a qualidade de código em Rails.

### SimpleCov

SimpleCov é uma ferramenta de análise de cobertura de teste para código em Ruby.

### MetricFu

MetricFu é um compilado de diversas ferramentas que ajudam a encontrar partes do código que podem ser melhoradas. No projeto será utilizado o MetricFu para a análise, utilizando todas as ferramentas mencionadas neste documento.

## 5. Referências Bibliográficas

PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.

MOURAO JUNIOR, Carlos Alberto  and  FARIA, Nicole Costa. Memória. Psicol. Reflex. Crit. [online]. 2015, vol.28, n.4, pp.780-788. Available from: <http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0102-79722015000400017&lng=en&nrm=iso>. ISSN 0102-7972.  http://dx.doi.org/10.1590/1678-7153.201528416.

SARAIVA, V. A. 2006. "UTILIZAÇÃO DA ABORDAGEM GOAL-QUESTION-METRICS (GQM) NA ELABORAÇÃO E EXECUÇÃO DE PLANOS DE AVALIAÇÃO DE USABILIDADE DE SOFTWARE : UM ESTUDO EMPÍRICO SOBRE UM SOFTWARE AGROPECUÁRIO".

