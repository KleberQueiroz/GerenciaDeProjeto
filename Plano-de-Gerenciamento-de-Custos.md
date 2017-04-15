
***
### Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
| 22/03/2017 | 0.1 | Estrutura de Tópicos | Daniel Moura |
| 25/03/2017 | 0.2 | Introdução e Estimação dos Custos | Daniel Moura |
| 28/03/2017 | 1.0 | Adicionando tópicos restantes  | Daniel Moura |

-----

[1. Introdução](#1-introdução)  
[2. Processos de Gerenciamento de Custo](#2-processos-de-gerenciamento-de-custo)  
[3. Unidades de Medida e Precisão](#3-unidades-de-medida-e-precisão)  
[4. Regras de Medição de Desempenho](#4-regras-de-medida-de-desempenho)  
[5. Custos com Recursos Humanos](#5-custos-com-recursos-humanos)  
[6. Custos com Aquisições](#6-custos-com-aquisição)  
[7. Orçamentos](#7-orçamento)    
[8. Referências Bibliográficas](#8-referências-bibliográficas)   

------------------------------------

## 1. Introdução

O objetivo deste documento é apresentar o Plano de Gerenciamento de Custos do projeto LocalizaçãoDarcy e como eles serão planejados, estruturados e controlado (PMBOK, p. 198). Os tópicos abordados serão os processos de gerenciamento de custo, unidades de medida e precisão, regras de medição de desempenho e formatos de relatório.

## 2. Processos de Gerenciamento de Custo

### 2.1. Estimar Custos
"É o processo de desenvolvimento de uma estimativa de custos dos recursos monetários necessários para terminar as atividades do projeto. O principal benefício deste processo é a definição dos custos exigidos para concluir os trabalhos do projeto." (2013). Guia PMBOK (5 ed., Vol., pág. 200). GlobalStandart.

### 2.2. Determinar Orçamento
Determinar o orçamento agrega os custos estimados das atividades para estabelecer uma linha de base. Foi utilizada a técnica PERT (Program Evaluation and Review Techinique) para estabelecer a duração de todas as atividades, e com base na duração foi calculado o custo de uma atividade multiplicando o valor em horas da atividade pelo custo de trabalho de um estudante por hora.
O orçamento do projeto será determinado tendo como base a estrutura analítica do projeto (EAP), as estimativas de custo e os recursos necessários ao projeto. Para determinar o orçamento, será utilizada a opinião especializada, sob a ótica da experiência geral da equipe em relação ao desenvolvimento, bem como os recursos mínimos para garantir um fluxo de trabalho constante. Tal atividade terá como saída um documento contendo a linha de base de desempenho dos custos.

### 2.3. Controlar Custos

O controle de custos terá como base o plano de gerenciamento de custos e informações coletadas acerca do desempenho do trabalho dos envolvidos no projeto. Esse controle será feito por meio do gerenciamento do valor agregado.

As principais dimensões analisadas serão o valor planejado (VP), estimado, em horas, pela gerência do projeto, o valor agregado (VA), que representa o valor do trabalho terminado - calculado por meio da multiplicação das horas planejadas pela porcentagem concluída de cada atividade - e o custo real (CR), que expressa o quanto foi efetivamente gasto na execução do trabalho - calculado pela multiplicação das horas gastas pelos integrantes do projeto pelo preço da hora de cada um. Com tais valores obtidos, serão calculados e gerenciados a variação de custos - VC, definida pela diferença entre o valor agregado e o custo real. Essa taxa de variação será convertida em índice de desempenho de custos. Ambos serão detalhados posteriormente.

O controle dos custos será feito tendo como base as estimativas explicadas no tópico anterior. Cada uma das estimativas obtidas deverá ser interpretada pela equipe de gerência. A partir dessa interpretação, a equipe deverá identificar o problema (se houver) e apontar as medidas mitigadoras/preventivas para o problema identificado. Todos esses dados poderão ser visualizados no relatório de desempenho das iterações.

| Indicador | Descrição | Fórmula | Parâmetros |
|-----------|-------------------------------------|----------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| BCWP | Custo Orçado do Trabalho Executado. | Percentagem do Projeto Realizado x Custo Total Planejado | Sem parâmetros |
| ACWP | Custo Real do Trabalho Realizado. | Horas Reais Gastas x Valor de Trabalho por hora | Sem parâmetros |
| BCWS | Valor Planejado | Horas Planejadas x Valor de Trabalho por hora | Sem parâmetros |
| CV | Variação do Custo do Projeto | BCWP - ACWP | CV > 0; Valor agregado abaixo do planejado / CV< 0; Valor agregado inferior ao que se gastou. |
| SV | Variação do Cronograma | BCWP - BCWS | SV > 0; Projeto Adiantado / SV < 0; Projeto Atrasado |
| SPI | Índice de Desempenho de Prazos | BCWP / BCWS | SPI > 1; Adiantado / SPI = 1; Custo conforme planejado / SPI < 1; Atrasado |
| CPI | Índice de Desempenho dos Custos | BCWP / ACWP | CPI > 1; Mais baixo que o planejado / CPI = 1; Custo conforme o planejado / CPI < 1; Custo mais alto que o planejado |

## 3. Unidades de Medida e Precisão

As unidades de medida dos recursos a serem utilizadas e suas respectivas precisões esperadas estão descritas na tabela abaixo:

| Recurso | Unidade de Medida | Cálculo | Precisão |
|:---:|:---:|:---:|:---:|
| Integrante da Equipe de Desenvolvimento | Reais (R$) | (Tempo de Trabalho) x (Preço do Tempo de Trabalho) | Preço do tempo de trabalho em reais e tempo de trabalho em horas |
| Integrante da Equipe de Gerência | Reais (R$) | (Tempo de Trabalho) x (Preço do Tempo de Trabalho) | Tempo de trabalho em horas e preço do tempo de trabalho em reais |
| _Coaches_ | Reais (R$) | (Tempo de Trabalho) x (Preço do Tempo de Trabalho) | Tempo de trabalho em horas e preço do tempo de trabalho em reais |

## 4. Regras de Medição de Desempenho

A medição de desempenho dos custos será dada pelo Gerenciamento do Valor Agregado (GVA). Esse gerenciamento será baseado na Variação do Custo e no Índice de Desempenho de Custo.

A Variação do Custo (_Cost Variance_ ou CV) é calculada pela diferença entre o Valor Agregado (_Earned Value_ ou EV) e o Custo Real (_Actual Cost_ ou AC).
<p align = "center" >CV = EV - AC

O Índice de Desempenho de Custo (_Cost Performance Index_ ou CPI) é calculado pela razão entre o Valor Agregado (_Earned Value_ ou EV) e o Custo Real (_Actual Cost_ ou AC).
<p align = "center" >CPI = EV / AC

## 5. Custos com Recursos Humanos
O cálculo hora/aluno foi feito com base no Relatório de Gestão do ano de 2015 da UnB, onde é indicado o custo anual de R$ 11.029,00 para cada aluno. Levando em conta que cada crédito corresponde a 15 horas mensais, e que o curso requer 240 créditos para ser concluído, chegamos ao total de 720 horas anuais.

1. Custo médio por aluno/hora[CaH]:

2. ((custo anual por aluno)))÷((Créditos da Engenharia de Software ÷ 5 anos) × 15 horas por crédito)
** ((R$ 11.029,00) ÷ ((240 ÷ 5 ) × 15)) = R$ 15,30 /h

Este valor serviu para estimarmos o custo da mão de obra, o cálculo foi feito utilizando a seguinte fórmula: 10hrs/semana × R$ 15,3/hr × 13 integrantes equipe.

## 6. Custos com Aquisições
### 6.1.	Notebooks
Os notebooks utilizados no projeto foram adquiridos individualmente por cada membro da equipe, uma vez que o uso de cada um será pessoal. A escolha dos notebooks também foi pessoal, o que causou uma certa discrepância nos valores das máquinas.
Dessa forma, foi feito um estudo para identificar os custos com computadores, baseando-se no número de projetos que poderiam ser desempenhados com essas máquinas e o tempo de vida de cada computador.

### 6.1.1.	Vida útil dos Notebooks
Segundo um relatório da microsoft na Worldwide Developer Conference de 2010, a idade média dos PC's da época eram de 4.4 anos. Há diversas recomendações para que a troca de computadores seja feita a cada 4 anos. Para empresas, a recomendação mais comum é que a troca seja feita a cada 3 anos.
Baseado nessas informações, a equipe estimou que nossos computadores serão úteis por 3 anos.

### 6.1.2.	Média de projetos por notebook
Considerando que o tempo gasto por integrante foi de 10 horas semanais, e que uma equipe de desenvolvimento em uma companhia trabalha durante 40 horas, seria possível realizar 4 projetos similares em 1 semestre. Logo, durante 3 anos, 24 projetos similares poderiam ser executados.

### 6.1.2.	Preço individual dos notebook

| Marca ou modelo | Preço |
|:----:|:------:|
| Dell | 2300 |
| Asus | 8000 |
| Macbook 13 | 10000 |
| Macbook 15 | 15000 |
| Acer | 1200 |
| Dell | 2000 |
| Dell | 2500 |
| Dell | 2300 |
| Itautec | 1000 |
| Samsung | 1500 |
| Samsung | 2000 |
| Asus | 2500 |
| Asus | 2000 |

Total: R$ 49.800,00

 O custo total com o maquinário foi de R$ 49.800,00. Idealmente, esse custo seria dividido entre 24 projetos e o impacto desses gastos nesse projeto seria de: R$ 2075,00.


### 6.2.	Transporte
O custo com transporte foi estimado com base no preço da passagem no DF, levando em conta que os membros da equipe teriam que pegar entre 2 e 4 linhas para ir a cada reunião. Logo, R$ 4,00 × 4 linhas/dia × 16 reuniões = R$256 x 13 membros R$ 3.328,00.
### 6.3.	Locação de espaço
As reuniões ocorrerão nas salas da própria faculdade. Levando em conta o tamanho do espaço e a infra-estrutura que ele oferece, foi feita uma pesquisa e o preço médio de locação de uma sala de reuniões com o mesmo padrão é de em média R$ 650,00 X 4 meses dando um total de R$ 2.600,00.

## 7. Orçamento
Definidos os riscos que tem o maior impacto, e como isso pode influenciar direta ou indiretamente na execução do projeto, foi estipulada uma reserva para possíveis imprevistos/mudanças. Essa reserva corresponde a 5% do valor estimado do projeto.

A escolha de 5% do valor total do projeto se deu após uma análise dos custos e dos riscos, como mudanças tardias no RUP são caras, a reserva se dá para tentar mitigar um possível aumento no custo do projeto. Caso não ocorra nenhuma mudança e o valor final seja correspondente ao valor estimado, 5% é um valor irrisório a ser pago, levando em consideração o benefício que isso pode trazer.


## 8. Referências Bibliográficas

* PMI (PROJECT MANAGEMENT INSTITUTE). Um Guia do Conhecimento em Gerenciamento de Projetos (Guia PMBOK®) – Quinta Edição. Newtown Square: Project Management Institute, 2009.

* UNB, Secretaria de Comunicação. GESTÃO 2012 − 2016: RELATÓRIO ILUSTRADO. 1. Disponível em: <http://www.noticias.unb.br/images/Noticias/2016/Documentos/Relatorio_Ilustrado_arquivo_web.pdf>. Acesso em: 25 mar. 2017.