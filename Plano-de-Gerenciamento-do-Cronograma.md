## Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|03/04/2017|1.0|Criação da estrutura do documento|Alexandre Torres|
|03/04/2017|1.0|Finalizados tópicos 1, 2, 3, 8, 9|Alexandre Torres|
***

## Sumário

1. [Introdução](#1-introdução)

2. [Precisão e Unidades de Medidas Utilizadas](#2-unidade_medida_precisao)

3. [Processo para a Definição do Cronograma do Projeto](#3-definicao_cronograma)

4. [Processo para a Manutenção do Cronograma do Projeto](#4-manutencao_cronograma)

5. [Procedimentos Organizacionais Associados](#5-procedimentos_organizacionais)

6. [Regras para a medição de desempenho](#6-medicao_desempenho)

7. [Cronograma](#7-cronograma)

8. [Referências](#8-referencias)

***





## 1. Introdução

 Planejar o gerenciamento do cronograma é estabelecer as políticas, procedimentos e documentação para planejar, desenvolver, gerenciar, executar e controlar o cronograma do projeto. O plano de Gerenciamento do Cronograma, segundo o _PMBOK_, estabelece os critérios e as atividades para o desenvolvimento e o controle do cronograma do projeto, que por sua vez tem como finalidade não só ser um guia para o desenvolvimento do projeto, mas também um mecanismo para auxiliar na pontualidade das entregas.

## 2. Precisão e Unidades de Medidas Utilizadas

A unidade de medida básica utilizado nesse projeto para realizar a análise do tempo gasto com cada atividade será baseada em horas ou dias. Ambas as unidades de medida são proporcionais, dessa forma, o resultado de uma medição ao utilizar qualquer uma delas será equivalente. A decisão de escolher uma em favor da outra, será associada a facilitar a compreensão e manipulação dos dados.

A medida de dias define o prazo no qual as atividades deverão ser desenvolvidas, ou seja, a sua duração. Dessa forma, será definido uma data de início e uma de término para cada tarefa.
A medida de hora tem como finalidade, monitorar o tempo gasto por cada indivíduo do grupo nas tarefas especificadas. Por ser uma unidade de medida mais , ela é mais indicada para análises mais "precisas".
Esse resultado desse monitoramento será um insumo para a análise dos gastos do projeto e índices de produtividade da equipe.

É interessante notar, que caso a coleta de dados relacionados a tempo seja feita de forma extremamente precisa, levando em conta cada segundo, a produtividade dos indivíduos será impactada negativamente, visto que haverá preocupações adicionais. Dessa forma, haverá o controle de horas, mas esse será feito de maneira moderada, de tal forma que o restante do projeto não seja impactado. Um bom threshold para isso, seria 90% de precisão.


## 3. Processo para a Definição do Cronograma do Projeto

O processo de definição do Cronograma é feito de de forma iterativa, visto que o cronograma não é um documento imutável ao longo do projeto. Porém, nesse tópico será discutido o processo a ser seguido a fim de elaborar a versão inicial do cronograma. 

É recomendado definir o Escopo do projeto e criar a EAP do projeto antes de iniciar a definição do Cronograma do projeto. Dessa forma, será possível identificar atividades das quais será possível estimar as durações.

**1) Definir as atividades:** Consiste em definir as atividades que serão realizadas ao longo do projeto e listá-las. As atividades podem ser relacionadas ao desenvolvimento ou a gerência do projeto.

**2) Sequenciar as atividades:** Identificar as dependências entre as atividade de tal forma que seja possível identificar a ordem de execução recomendada para esse grupo de atividades.

**3) Estimar os recursos das atividades:** Deve-se estimar a duração das atividades a serem desenvolvidas. Para isso, é possível consultar um especialista, basear-se em projetos semelhantes anteriores, ou até mesmo utilizar técnicas como a PERT, que aproxima a estimativa da duração da atividade como sendo uma média ponderada das estimativas de duração otimista, pessimista e esperada.

**4) Identificar o caminho crítico:** Essa etapa pode ser pulada, caso seja utilizada uma ferramenta voltada a construção de cronogramas, visto que essa análise normalmente é feita pela ferramenta. Nesse projeto será utilizada uma ferramenta. Porém, é interessante ressaltar a importância de identificar o caminho crítico. O caminho crítico está associado ao menor tempo possível necessário para a finalização do projeto. Dessa forma, se ele não for seguido, não estaremos otimizando o tempo necessário para a entrega do projeto.

**5) Desenvolver o cronograma:** A partir das informações obtidas previamente e da identificação do caminho crítico, deve-se construir o cronograma.

Nesse projeto utilizaremos o _Gantter_ como ferrementa para a criação do cronograma. Alguns dos motivos para a escolha foram a experiência prévia dos membros do grupo com a ferramenta, e a possibilidade de edição do cronograma online por todos os membros do grupo.


## 4. Processo para a Manutenção do Cronograma do Projeto

Para que haja a manutenção do cronograma é necessário monitorar e gerenciar as atividades de tal forma que seu progresso seja acompanhado. Dessa forma, será possível identificar a necessidade da realização de mudanças no cronograma.

O cronograma é um artefato essencial para guiar e monitorar o progresso do projeto, segundo o PMBOK. Com o correto acompanhamento do projeto, é possível minimizar riscos causados por atrasos e possíveis desvios das atividades essenciais para o bom andamento do projeto. 

O processo para manutenção do cronograma ocorre sempre que houver uma solicitação de mudança relacionada a alguma das atividades presentes no cronograma. Na necessidade de alterar o cronograma do projeto, o seguinte processo será seguido:

1. **Análise da necessidade da mudança:** Inicialmente, será confirmada a real necessidade de se alterar o cronograma. 
2. **Análise do impacto da mudança:** Serão identificados os impactos das mudanças ao longo do resto do projeto.
3. **Análise e registro do motivo da mudança:** Nessa etapa, será feita uma análise a fim de identificar o motivo da necessidade de mudança do cronograma. Essa análise deverá ser registrada para que erros similares sejam evitados no futuro.
4. **Análise da viabilidade da mudança:** Será nessa atividade em que a equipe de gerencia decidirá se a mudança no cronograma será feita. A viabilidade dependerá da necessidade e do impacto causados pela mudança.
5. **Replanejamento das atividades:** O processo de replanejamento das atividades segue o processo definido pelo tópico 3 (Processo para a Definição do Cronograma do Projeto).
6. **Atualização do cronograma:** A atualização do será baseada no que foi definido nos tópicos anteriores.


OBS: As decisões referentes ao processo serão tomadas pela equipe de gerenciamento do projeto.


## 5. Procedimentos Organizacionais Associados

O processo de definição e manutenção do cronograma está relacionado a diversas outras áreas de gerenciamento do projeto. Serão utilizados, portanto, alguns documentos do Plano de Gerenciamento do Projeto como base.

Os principais documentos associados são o Plano de gerenciamento do Escopo (incluindo EAP), o próprio cronograma, e dados baseados na produtividade da equipe de desenvolvimento. É importante notar que todos planos estão relacionados e são necessários para a correta definição, replanejamento do cronograma do projeto. Por exemplo, a duração e cronograma do projeto, depende do número e qualificação dos trabalhadores envolvidos, sendo importante o plano de gerenciamento de Recursos Humanos. A qualidade do projeto, também influencia a sua duração e cronograma, ou seja, é necessário utilizar como base plano de gerenciamento de qualidade. A limitação de custos do projeto também é um fator relevante, entre outros.

A EAP, contida no plano de gerenciamento de Escopo, contém informações sobre o que será entregue pelo projeto. O plano de gerenciamento do escopo, está associado ao gerenciamento dessas entregas. Já o cronograma é uma extensão, um detalhamento da EAP, contendo as atividades a serem executadas, as datas de início e finalização e os recursos necessários. Dessa forma, ao atualizar o escopo, é necessários atualizar também o cronograma. Somado a isso, o cronograma comumente é alterado para se adequar ao desempenho dos desenvolvedores, caso não estejam disponíveis dados históricos.


## 6. Regras para a Medição de Desempenho

É fundamental o acompanhamento do desempenho do projeto. Ao acompanhar o desempenho do projeto, pode-se:
* Utilizar dados a fim de definir o quão atrasado ou adiantado o projeto está.
* Analisar o grau de eficácia do planejamento do projeto.
* Aperfeiçoar o replanejamento do cronograma, baseando-se em dados históricos.
* Melhorar o controle para atingir o desempenho previamente definido.

Existem diversos métodos para análise de desempenho. Nesse projeto utilizaremos o Gerenciamento de Valor Agregado (GVA). Ele baseia-se na Variação do Cronograma e no Índice de Desempenho de Prazos.
O Índice de Desempenho de Prazos (Schedule Performance Index ou SPI) é calculado pela razão entre o Valor Agregado (Earned Value ou EV) e o Valor Planejado (Planned Value ou PV).
	SPI = EV / PV
O resultado obtido indica a eficácia do planejamento, e pode ser interpretada como:
* IDP < 1 - Sinal de atraso no projeto.
* IDP = 1 - Eficácia plena no planejamento
* IDP < 1 - Sinal de adiantamento no projeto.

Já a Variação do cronograma ( Schedule Variance ou SV) é calculada pela diferença entre o Valor Agregado (Earned Value ou EV) e o Valor Planejado (Planned Value ou PV). Ou seja, representa quantitativamente o atraso ou adiantamento do projeto com relação as entregas planejadas para uma data específica.
	SV = EV - PV
Caso o resultado se iguale a zero, exatamente o que foi planejado foi entregue.


## 7. Cronograma

[Cronograma do Projeto](https://github.com/fga-gpp-mds/2017.1-LocalizacaoDarcy/wiki/Cronograma)

## 8. Referências

* PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.