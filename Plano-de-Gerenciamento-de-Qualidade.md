# Plano de Gerenciamento dos Riscos

## Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|02/04/2017|0.1|Criação do documento|Eduardo Gomes|
|04/04/2017|0.2|Adição de Introdução e Processo de Qualidade|Eduardo Gomes|
|04/04/2017|0.3|Métricas e Ferramentas|Matheus Mello|

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

O processo de qualidade será dado a partir de uma sequência de passos definidos no PMBoK. As fases do processo de qualidade serão dados nas etapas de Planejamento, Execução e Monitoramento e Controle do projeto.

[![ProcessoDeQualidade.png](https://s29.postimg.org/wjrbm1ygn/Processo_De_Qualidade.png)](https://postimg.org/image/8g0jxrfzn/)

* Criar o planejamento da gerencia de qualidade: consiste na elaboração de um plano que contem a identificação dos requisitos ou padrões de qualidade do projeto. Realizar esse processo auxilia no fornecimento de orientações e instruções sobre como será validada e gerenciada a qualidade do projeto. 

* Garantir a qualidade: é o processo para garantir o uso de padrões de qualidade, de auditoria dos requisitos de qualidade e resultados de medição.

* Monitorar e controlar a qualidade do projeto: é dado ao monitorar, registrar para então avaliar o desempenho e recomendar mudanças no projeto. É benéfico ao projeto pois identifica causas da baixa qualidade e pode fazer recomendações para elimina-la e valida a conformidade do projeto para com as partes interessadas.

## 3. Ferramentas da análise de qualidade

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

## 4. Métricas

### Complexidade Ciclomática

Como indicador de complexidade ciclomática, adotou-se que serão aceitados apenas valores abaixo de 12, a parte do código que tiver este indicador acima de 12 deverá ser simplificada e até quebrada

|              **Indicador**                |            **Legenda**              |
|:-------------------------------:|:---------------------------:|
|0 - 5   |Excelente|
|6 - 12   |Razoável|
|acima de 12   |Ruim|

### Cobertura de Teste

|              **Indicador**                |            **Legenda**              |
|:-------------------------------:|:---------------------------:|
|acima de 90%   |Excelente|
|50% - 89%   |Razoável|
|30% - 49%   |Razoável|
|abaixo de 30%   |Ruim|

### Número de Caracteres por Linha

De acordo com o guia de estilo, cada linha deverá ter no máximo 80 caracteres.

### Número de Linhas por Método

Devido a alta distinção entre métodos, cada um tendo sua função específica. Esta métrica será utilizado apenas para fins informativos, para a averiguação dos resultados será utilizada a Complexidade Ciclomática, tendo como foco um bom design de operações.

## 5. Referências Bibliográficas

PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.