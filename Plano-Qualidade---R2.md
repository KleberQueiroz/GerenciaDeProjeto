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

#### 3.1.1 Melhorar a qualidade de código do software.
| Dimensão | Objetivo|
|-----------------------|---------------------|
| Analisar | Código do Software sendo desenvolvido |
| Com propósito de | Conhecer e Melhorar|
| Com respeito a | Qualidade |
| Sob ponto de vista dos | Desenvolvedores |
| No contexto do | Projeto OndeÉUnB |


#### 3.1.2 Melhorar a qualidade do processo de desenvolvimento.
| Dimensão | Objetivo|
|-----------------------|---------------------|
| Analisar | O processo  |
| Com propósito de | Verificar |
| Com respeito a | Qualidade |
| Sob ponto de vista do | Gerentes de Projeto (GPP) |
| No contexto de | Projeto de OndeÉUnB |


#### 3.1.3 Melhorar as estimativas de planejamento das sprints.
| Dimensão | Objetivo|
|-----------------------|---------------------|
| Analisar | Estimativas de Tempo  |
| Com propósito de | Verificar |
| Com respeito a | Acurácia do Planejamento |
| Sob ponto de vista do | Gerentes de Projeto (GPP) |
| No contexto de | Projeto de OndeÉUnB |


### 3.2. Perguntas

<p align="justify">Perguntas ou Questões são definidas a partir dos objetivos estabelecidos para obter informações sobre os mesmos. Para cada fator de qualidade registrado no Abstraction Sheet é gerada uma mais perguntas que nada mais serão do que um resultados para o objetivo de mensuração.

#### 3.2.1. As perguntas elaboradas relacionadas aos objetivo **Melhorar a qualidade de código do software** foram:

* A compreensibilidade do código está boa? 


* A estrutura do código está boa? 


* O código está bem testado?


#### 3.2.1. As perguntas elaboradas relacionadas aos objetivo **Melhorar a qualidade do processo de desenvolvimento** foram:

* Como foi a produtividade da equipe na última sprint?


* Como foi a integração da equipe na última sprint?


* O processo está sendo seguido facilmente pela equipe?


* Como está a qualidade dos artefatos gerados ao aplicar esse processo?


#### 3.2.1. As perguntas elaboradas relacionadas aos objetivo **Melhorar as estimativas de planejamento das sprints** foram:

* Qual o percentual do planejado foi executado?


* A duração e a quantidade de pontos planejadas para essa sprint foi boa? 



### 3.3. Métricas
As métricas abaixo serão divididas de acordo como os objetivos definidos, e posteriormente identificaremos quais perguntas elas respondem.


#### 3.3.1. Com a finalidade de atingir o objetivo “Melhorar a qualidade de código do software” foram definidas as seguintes métricas e sua importância para responder as perguntas associadas.


##### M1. Complexidade

<p align="justify">Segundo uma pesquisa sobre psicologia cognitiva, um indivíduo consegue armazenar em sua memória de 5 a 9 objetos simultaneamente (MOURÃO, 2015). Por isso, um desenvolvedor ao analisar o código e necessitar dar uma manutenção ao mesmo teria uma dificuldade maior em assimilar 6 caminhos diferentes ou mais, o ideal seria que no máximo o código tivesse 5 caminhos, por isso foi escolhida a complexidade média foi de  5.

| M1 | Complexidade |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Complexidade de código |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso seja alta a complexidade, o código deverá ser refatorado. |
| Meta | A complexidade será considerada: Baixa < 5, Regular = 5, Alta > 5. |
|Ferramenta| Code Climate/Rubocop|

##### M2. Cobertura de Testes

<p align="justify">A cobertura de testes possui um caráter de analisar dinamicamente o produto. É uma atividade para a identificação e eliminação de erros que possam persistir. O conjunto de informações obtidas a partir dos testes de software tem grande valor para atividades como a manutenção, depuração e estimativa de confiabilidade de software (MALDONADO, 2007).

| M2 | Cobertura de Testes |
|-------------------|----------------------------------------------------------------------------------------|
| Medida | Funcionalidades/Total de Funcionalidades |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso metas não sejam atingidas, buscar entender motivos e e tomar decisões corretivas. |
| Meta | Testes R1 > 30%, Testes R1 > 90% |
|Ferramenta|SimpleCov, Cucumber, rspec|

##### M3. Tamanho de Classes

<p align="justify">Com o objetivo de manter uma boa modularização do código, será calculado a quantidade de linhas de cada classe.

| M3 | Tamanho da Classe |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Linhas por classe |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Caso seja ultrapassada a meta, o código deverá ser refatorado. |
| Meta | Cada classe deve ter no máximo 100 linhas de código |
|Ferramenta| Code Climate/Rubocop|


##### M4. Linhas por método

<p align="justify">Devido a alta distinção entre métodos, cada um tendo sua função específica. Esta métrica será utilizado apenas para fins informativos e possivelmente para refatoração.

| M4 | Linhas por Método - ABC Metric |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Pontuação Linhas por Método |
| Período de coleta | Após o desenvolvimento dos Casos de Uso da R1 e ao final de cada Sprint na R2 |
| Ação | Se o limite for ultrapassado, refatorar método. |
| Meta | Pontuação de 15 ou menor que 15. |
|Ferramenta| Code Climate/Rubocop|

##### M5. Percentual de Comentários por linhas de Código

| M5 | Percentual de Comentários por linhas de Código |
|-------------------|-------------------------------------------------------------------------------|
| Medida |  |
| Período de coleta |  |
| Ação |  |
| Meta |  |
|Ferramenta|  |


#### 3.3.2. Com a finalidade de atingir o objetivo “Melhorar a qualidade do processo de desenvolvimento” foram definidas as seguintes métricas e sua importância para responder as perguntas associadas.



##### M1. Variação nos pontos concluídos

| M1 | Variação nos pontos concluídos |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Número de pontos concluídos na sprint dividido pela quantidade média de pontos executados nas sprints anteriores (baseline).|
| Período de coleta | Ao fim de cada sprint |
| Ação | Caso esteja abaixo do esperado, a equipe deve se reunir para identificar os problemas que afetaram a conclusão das atividades. A ação dependerá dessa conclusão. |
| Meta | Acima de 80% |
| Ferramenta | Coleta Manual |


##### M2. Nível de Integração da Equipe

| M2 | Nível de Integração da Equipe |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Pergunta individual para os integrantes sobre como consideração sua integração da equipe seguindo uma escala de 0 a 5. A pergunta elaborada aos integrantes será: _"Avalie de 0 a 5 o quão bom você considera a sua integração e comunicação com o restante da equipe durante essa sprint"_. |
| Período de coleta | Ao fim de cada sprint, durante a sprint review. |
| Ação | Avaliar a alterar ferramentas de comunicação, conversar com o membro que se sentiu pouco integrado, realizar alterações no processo |
| Meta | Média de todos os integrantes do grupo como sendo no mínimo 3.3. |
| Ferramenta | Coleta Manual |

##### M3. Avaliação da dificuldade de se adequar as mudanças planejadas. 

| M3 | Avaliação da dificuldade de se adequar as mudanças planejadas|
|-------------------|-------------------------------------------------------------------------------|
| Medida | Para cada alteração na metodologia ou nas práticas realizada na sprint atual, os integrantes deverão informar o quão difícil foi se adequar a essas alterações (baseando-se nas sprints anteriores). A avaliação será subjetiva e irá variar de 0 a 5. A resposta a ser respondida será  _"Avalie de 0 a 5 o quão difícil você considera ter sido sua adequação a < prática ou metodologia modificada > nessa sprint"_. |
| Período de coleta | Ao fim de cada sprint |
| Ação | Avaliar se essa mudança será adotada ou não para as sprints restantes. |
| Meta | Não tem meta para essa métrica. Um valor baixo indica que é uma mudança difícil de ser aplicada, mas não necessariamente é negativa. |
| Ferramenta | Coleta Manual |


##### M4. Percentual de artefatos rejeitados 

| M4 | Percentual de artefatos rejeitados  |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Percentual de artefatos rejeitados devido a qualidade dividido pelo total de artefatos criados na sprint |
| Período de coleta | Ao fim de cada sprint, durante a sprint review |
| Ação | Caso esteja abaixo do esperado, a equipe deve se reunir para identificar os problemas que afetaram a conclusão das atividades. A ação dependerá dessa conclusão, poderão ser realizados treinamentos adicionais, alterações no processo, etc. |
| Meta | Acima de 75% de rejeição. |
| Ferramenta | Coleta Manual |


##### M5. Percentual de características negativas da sprint

| M5 | Percentual de características negativas da sprint  |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Quantidade de características negativas da sprint dividido pela soma das positivas com as negativas |
| Período de coleta | Ao fim de cada sprint, durante a retrospectiva |
| Ação | Caso esteja abaixo do esperado, a equipe deve se reunir para identificar os problemas que afetaram a qualidade da sprint. |
| Meta | Abaixo de 50% |
| Ferramenta | Coleta Manual |



#### 3.3.3. Com a finalidade de atingir o objetivo “Melhorar as estimativas de planejamento das sprints” foram definidas as seguintes métricas e sua importância para responder as perguntas associadas.

	****** REMOVER ******
	##### M1. Pontos Concluídos

	| M1 | Pontos Concluidos |
	|-------------------|-------------------------------------------------------------------------------|
	| Medida | Número de pontos concluídos na sprint |
	| Período de coleta | Ao fim de cada sprint |
	| Ação | Caso esteja abaixo do esperado, a equipe deve se reunir para identificar os problemas que afetaram a conclusão das atividades. A ação dependerá dessa conclusão, poderão ser realizados treinamentos adicionais, planejar menos pontos na sprint seguinte, etc. |
	| Meta | Acima de 80% do planejado. |
	| Ferramenta | Coleta Manual |


	##### M2. Pontos Planejados

	| M2 | Pontos Planejados |
	|-------------------|-------------------------------------------------------------------------------|
	| Medida | Número de pontos planejados para a sprint |
	| Período de coleta | No início de cada sprint |
	| Ação | Como o objetivo é encontrar a quantidade de pontos ideal para cada sprint, deve-se aumentar ou diminuir a quantidade de pontos de acordo com a restrospectiva e baseline de sprints anteriores. |
	| Meta | Ser igual ao pontos Concluídos e garantir que a equipe fique ocupada por 10 horas por dia. |
	| Ferramenta | Coleta Manual |



##### M3. Percentual dos pontos Concluidos

| M3 | Percentual dos pontos Concluidos |
|-------------------|-------------------------------------------------------------------------------|
| Medida | Número de pontos concluídos na sprint dividido pela quantidade de pontos planejados |
| Período de coleta | Ao fim de cada sprint |
| Ação | Caso esteja abaixo do esperado, a equipe deve se reunir para identificar os problemas que afetaram a conclusão das atividades. A ação dependerá dessa conclusão, poderão ser realizados treinamentos adicionais, planejar menos pontos na sprint seguinte, etc. Como o objetivo é encontrar a quantidade de pontos ideal para cada sprint, deve-se utilizar os dados obtidas nessa sprint a fim de planejar as sprints seguintes com um maior nível de acurácia. |
| Meta | Ideal: 100% - Recomendável: 80% - Crítico: 50% |
| Ferramenta | Coleta Manual |

##### M4. Média de horas para a execução das atividades 

->OBS: A duração e a quantidade de pontos planejadas estão diretamente relacionadas... Dessa forma é mais interessante verificar o esforço gasto semanalmente. Se foi gasto muito mais de 10 horas , a sprint deveria ser maior com a mesma quantidade de pontos ou do mesmo tamanho com menos pontos.

| M4 | Média de horas para a execução das atividades |
|-------------------|-------------------------------------------------------------------------------|
| Medida |  |
| Período de coleta | Ao fim de cada sprint, durante a sprint review |
| Ação | Aperfeiçoar o planejamento da sprint seguinte. |
| Meta | Recomendável: 10 horas. Aceitável: entre 8 e 13 |
| Ferramenta | Coleta Manual |



### 3.4. Utilizando as Métricas para responder as perguntas
Será explicado como as métricas serão utilizadas a fim de responder as perguntas elaboradas.

#### 3.4.1. Com a finalidade de atingir o objetivo “Melhorar a qualidade de código do software” foram definidas as seguintes as perguntas associadas.


##### 3.4.1.1. A compreensibilidade do código está boa?

A fim de analisar a compreensibilidade do código, serão utilizadas as métricas "Percentual de Comentários”, ”Tamanho de Classes” e "Linhas por método”, visto que as duas últimas sugerem o quão coeso o software está, e um software coeso é de mais fácil compreensão para humanos.

FORMULA de como será calculado

##### 3.4.1.2. A estrutura do código está boa? 

A fim de analisar a estrutura do código, será utilizada principalmente a Métrica  “Complexidade”. Porém em conjunto com, serão utilizadas as métricas "Tamanho de Classes” e "Linhas por método” que podem sugerir o quão coeso o software está, o que influencia na qualidade de sua estruturação.

FORMULA de como será calculado


##### 3.4.1.3. O código está bem testado?

Será utilizada a Métrica “Cobertura de Testes” como base. Conforme especifico anteriormente no relatório a cobertura deve ser maior que 90%.

#### 3.4.2. Com a finalidade de atingir o objetivo “Melhorar a qualidade do processo de desenvolvimento” foram definidas as seguintes as perguntas associadas.


##### 3.4.2.1. Como foi a produtividade da equipe na última sprint?

Será utilizados a métrica "Variação nos pontos concluídos”. Dessa forma, será comparado a quantidade de pontos concluídos nessa sprint com os dados registrados de sprints anteriores (baseline). Dessa forma, será possível  identificar melhorias ou pioras no desempenho da equipe ao serem realizadas alterações na metodologia utilizada. Apesar disso, não será possível comparar o desempenho da equipe desse projeto com outras equipes utilizando somente essa métrica.

##### 3.4.2.2. Como foi a integração da equipe na última sprint?

Será utilizados a métrica "Nível de Integração da Equipe”. 

EXPLICAR


##### 3.4.2.3. O processo está sendo seguido facilmente pela equipe?

Será utilizados a métrica "Avaliação da dificuldade de se adequar as mudanças planejadas”. 

EXPLICAR

##### 3.4.2.4. Como está a qualidade dos artefatos gerados ao aplicar esse processo?

Será utilizados a métrica "Percentual de artefatos rejeitados”. E as métricas de qualidade de código ("Complexidade”, ”Cobertura de Testes”, "Tamanho de Classes”, "Linhas por método", "Percentual de Comentários por linhas de Código"

EXPLICAR COMO / FORMULA


#### 3.4.2. Com a finalidade de atingir o objetivo “Melhorar a qualidade do processo de desenvolvimento” foram definidas as seguintes as perguntas associadas.



##### 3.4.2.1. Qual o percentual do planejado foi executado?

Será utilizados a métrica "Percentual dos pontos Concluidos”.


##### 3.4.2.2. A duração e a quantidade de pontos planejadas para essa sprint foi boa? 

Será utilizados a métrica "Média de horas para a execução das atividades”.



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