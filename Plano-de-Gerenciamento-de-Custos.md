
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
Os notebooks utilizados no projeto foram adquiridos individualmente por cada membro da equipe, uma vez que o uso de cada um será pessoal. A escolha dos notebooks também foi pessoal, o que causou uma certa discrepância nos valores das máquinas. O custo total com o maquinário foi de R$ 39.000,00, o que gerou uma média de R$ 3.000,00 por máquina.
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
