## Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|15/03/2017|1.0|Criação da estrutura do documento|Rafael Rabetti|
|15/03/2017|1.1|Introdução, riscos, cronograma e interessados|Rafael Rabetti|
|15/03/2017|1.2|Objetivo, Visão geral, Motivação|Eduardo Brasil|
|22/03/2017|1.3|Objetivo, Visão geral, Motivação|Rafael Rabetti|
|28/03/2017|1.4|Resumo do Orçamento|Rafael Rabetti|


***

## Sumário
1.   [Introdução](#1-introdução)

2.   [Visão Geral e Objetivo](#2-visão-geral-e-objetivo)

3.   [Motivação](#3-motivação)

4.   [Riscos](#4-riscos)

5.   [Resumo do Cronograma de Marcos](#5-resumo-do-cronograma-de-marcos)

6.   [Resumo do Orçamento](#6-resumo-do-orçamento)

      6.1 [Custos com Recursos Humanos](#61-custos-com-recursos-humanos)

      6.2 [Custos com Equipamentos e Serviços](#62-custos-com-equipamentos-e-serviços)

      6.3 [Estimativa](#63-estimativa)

7.   [Interessados](#7-interessados)

## 1. Introdução

O presente documento visa introduzir e mostrar as características do projeto Sistema de Localização no campus Darcy Ribeiro. Consequentemente, será apresentada a visão geral do projeto, seus objetivos, quais motivações levaram ao seu desenvolvimento, os riscos envolvidos e os interessados no projeto.

## 2. Objetivo e Visão geral

Este projeto tem como proposta apresentar um software que auxilie na localização dos visitantes, novos frequentadores e calouros dentro do campus Darcy Ribeiro da Universidade de Brasília. Com isso, objetiva-se que os atrasos em compromissos diminuam e que não haja pessoas desorientadas dentro da universidade.

#### Restrições do projeto

* O Sistema deve ser implementado utilizando a linguagem Ruby com o framework para desenvolvimento web Rails.
* O sistema deve ser um Web-Site, e deve oferecer suporte aos browsers Google Chrome, Mozilla Firefox, Safari, Internet Explorer e Microsoft Edge. Além disso, o Web-Site deverá ser responsivo, podendo assim ser visualizado nas plataformas mobile.
* O projeto tem um prazo fixo para ser desenvolvido, pois será desenvolvido por alunos de uma disciplina com duração fixa.

## 3. Motivação 

Todo início de semestre muitos calouros ficam perdidos no campus Darcy Ribeiro, perguntando onde ficaria tal prédio ou departamento. O novo aluno demora para se habituar com o novo local de estudos, devido à grande dimensão do campus Darcy Ribeiro. Até estar habituado, o aluno se atrasa para as suas aulas e acaba até recebendo falta.  

O campus Darcy Ribeiro possui uma área total de 3.950.569,07 m², porém a área construída é de 513.767, 16 m², o que ainda é muito grande. Atualmente não há nenhuma tecnologia que atenda à essa demanda. A maioria desses novos frequentadores acabam recorrendo ao *Google Maps* que, às vezes, não atende à expectativa.

A motivação surgiu por conta dessa grande dimensão do campus Darcy Ribeiro, pois devido às suas proporções, às vezes se torna complicado a localização de prédios e departamentos, principalmente para pessoas que não estão familiarizadas com o campus, como alunos que acabaram de ingressar no campus ou pessoas que se encaminham ao mesmo para realização de provas de concursos públicos e até mesmo pesquisadores de outras universidades. Com isso surgiu uma demanda de projeto vinda do CPD (Centro de Informática) da própria universidade com o objetivo de auxiliar esse público alvo.

## 4. Riscos 

* **Capacitação Técnica**

A tecnologia Ruby on Rails é nova para a maioria dos membros da equipe e isso pode trazer alguma dificuldade na produção. 

* **Recursos**



* **Desistência de Aluno**

Como o projeto está no contexto de disciplinas de graduação, caso algum aluno desista, isso pode trazer dificuldades à equipe.

* **Prazo de Entrega Fixo**

Como o prazo de entrega não é negociável, atrasos no cronograma podem trazer dificuldades.

## 5. Resumo do Cronograma de Marcos

Este projeto possui dois marcos principais de entrega do produto: Release 1 e Release 2.

| | |
|-|-|
|**Data**|**Entrega**|
|22/04/2017 <br /> --------------- <br /> Release 1| Toda documentação e versão funcional inicial.|
|26/06/2017 <br /> --------------- <br /> Release 2| Todas as funcionalidades concluídas e documentação finalizada.|

## 6. Resumo do Orçamento

### 6.1 Custos com Recursos Humanos
O cálculo hora/aluno foi feito com base no Relatório de Gestão do ano de 2015 da UnB, onde é indicado o custo anual de R$ 11.029,00 para cada aluno. Levando em conta que cada crédito corresponde a 15 horas mensais, e que o curso requer 240 créditos para ser concluído, chegamos ao total de 720 horas anuais.

* Custo médio por aluno/hora[CaH]:

* ((custo anual por aluno)))÷((Créditos da Engenharia de Software ÷ 5 anos) × 15 horas por crédito) ** ((R$ 11.029,00) ÷ ((240 ÷ 5 ) × 15)) = R$ 15,30 /h

Este valor serviu para estimarmos o custo da mão de obra, o cálculo foi feito utilizando a seguinte fórmula: 10hrs/semana × R$ 15,3/hr × 13 integrantes equipe.

### 6.2 Custos com Equipamentos e Serviços

Somando os valores das aquisições cada integrante, transporte e locação de espaço, temos um custo total de R$ 52.728, 00. O cálculo de cada valor pode ser visto no [Plano de Gerenciamento de Custos](https://github.com/fga-gpp-mds/2017.1-LocalizacaoDarcy/wiki/Plano-de-Gerenciamento-de-Custos).

### 6.3 Estimativa

O custo total estimado consiste no somatório entre os custos de Recursos Humanos e Equipamentos e serviços, o resultado é expresso pela fórmula abaixo:

Recursos Humanos + Equipamentos e Serviços = R$ 31.824,00 + R$ 52.728,00 = R$ 84.552,00

## 7. Interessados

* **CPD**

A diretoria do CPD da UnB é o cliente do projeto. O CPD fornece os dados necessários para o desenvolvimento e implementação do projeto aqui apresentado.

* **Visitantes e novos frequentadores do campus Darcy Ribeiro**

Gostariam de se localizar facilmente dentro do campus.

* **Docente**

A professora Carla Rocha, a qual ministra as disciplinas Gerência de Projetos e Portifólio de Software e Métodos de Desenvolvimento de Software na Universidade de Brasília campus Gama, é a avaliadora do produto final.

* **Equipe de Gerência de Projetos e Portifólio de Software**

Esta equipe é formada por alunos de graduação de Engenharia de Software da Universidade de Brasília campus Gama que cursam a disciplina Gerência de Projetos e Portifólio de Software.

|              **Nome**                |            **__Email__**              |      **GitHub** |
|:-------------------------------:|:---------------------------:|:---------------------------:| 
|Eduardo Brasil Martins   |<brasil.eduardo1@gmail.com>| [EduardoBrasil](https://github.com/EduardoBrasil)|
|Daniel Moura da Silva        |<danmoura17@gmail.com>| [danmoura17](https://github.com/danmoura17) |
|Rafael dos Santos Rabetti    |<rafael.rabetti@gmail.com> |[rafaelrabetti](https://github.com/rafaelrabetti) |
|Eduardo Quintino Gomes       | <eduardoqgomes@gmail.com>| [eduqg](https://github.com/eduqg)|
|Alexandre Torres Kryonidis     |<alexandrekry@gmail.com> |[alexandretk](https://github.com/alexandretk) |
|Matheus Mello | <mat.mello93@gmail.com>    | [matmello](https://github.com/matmello)|

* **Equipe de Métodos de Desenvolvimento de Software**

Esta equipe é formada por alunos de graduação de Engenharia de Software da Universidade de Brasília campus Gama que cursam a disciplina Métodos de Desenvolvimento de Software.


|              **Nome**                |            **__Email__**             |     **GitHub** |
|:-------------------------------:|:---------------------------:|:---------------------------:| 
|Lucas Soares Souza	|<lucas.soaresouza@gmail.com>|  [lucassoaresouza](https://github.com/lucassoaresouza)| 
|Jordan de Oliveira Miranda   |<jordan.oliveira.m@gmail.com>| [JordanMiranda](https://github.com/JordanMiranda) |
|Stéfane Bogéa de Souza	   |<stefanesouza04@gmail.com>| [stefanesouza](https://github.com/stefanesouza)|
|Mateus Vieira da Silva Roriz	 |<mateusvroriz6b@gmail.com>|[mateusvroriz](https://github.com/mateusvroriz) |
|Sannya Santana de Arvelos	|<sannyasantana@gmail.com>| [SannyaArvelos](https://github.com/SannyaArvelos)|
|Taynara de Jesus Carvalho	|<tayhcarvalho@gmail.com>| [tayh](https://github.com/tayh)|
|Kairon			|     <kairon.vzb@gmail.com>            | [kairon-v](https://github.com/kairon-v)|