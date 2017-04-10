## Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|30/03/2017|1.0|Criação da estrutura do documento|Alexandre Torres|
|30/03/2017|1.0|Adicionados tópicos 1, 2, 3|Alexandre Torres|
***

## Sumário

1. [Introdução](#1-introdução)

2. [Processo de Gerenciamento do Escopo](#2-processo_gerenciamento_escopo)

2.1. [Planejar o gerenciamento do Escopo](#2.1-planejar_gerenciamento_escopo)

3. [Definição e validação do Escopo](#3-definições)
3.1. [Processo de definição do Escopo](#3.1-processo_definicao_escopo)

4. [Desenvolvimento e Manutenção da Estrutura Analítica do Projeto - EAP](#4-desenvolvimento_eap)

5. [Gestão de Mudanças do Escopo](#5-gestao_mudanca)

6. [Referências Bibliográficas](#6-referencias_bibliograficas)



## 1. Introdução

O objetivo desse documento é documentar como o escopo do projeto OndeEUnb será definido e gerenciado. O escopo está relacionado as características e funções que caracterizam o sistema a ser desenvolvido, ou seja, as regras do que o projeto abrangerá ou não abrangerá. Nesse documento será descrito o processo para a sua definição e gerenciamento. Será incluído também o processo de desenvolvimento e manutenção da Estrutura Analítica do Processo (EAP).


## 2. Processo de Gerenciamento do Escopo

A fim de melhorar a compreensão de como será o processo de gerenciamento do escopo, foi desenhado o seguinte processo.

As atividades desse processo serão detalhadas ao longo desse documento.


#### 2.1. Planejar o gerenciamento do Escopo

O objetivo desse planejamento é basicamente documentar como o escopo será definido, validado e controlado. Ele é elaborado pela equipe de gerência do projeto e consiste de entradas e saídas.

Como os planos de gerenciamento estão interligados direta ou indiretamente, diversos planos podem ser utilizados como entrada para esse, e ao mesmo tempo esse pode ser entrada para outros. Como exemplo, podemos citar o fato de que o escopo dependerá do tempo de projeto, da limitação financeira, da qualidade do produto, entre outros, dependendo, portanto, de outros planos.

O principal artefato de saída relacionado a esse plano será a EAP (Estrutura Analítica de Projeto).

## 3. Definição e validação do Escopo

O tema do projeto surgiu como uma demanda da Universidade de Brasilia. Ao conversar com os interessados, foi decidido que o grupo de desenvolvimento seria o responsável pela definição do escopo que, posteriormente, seria validado pelo cliente. A definição, portanto, será feita inicialmente pelos integrantes dos grupos de GPP e MDS utilizando a técnica de Brainstorming. Posteriormente, o projeto será validado pelo cliente, quem também fará sugestões de melhorias.

A fim de validar o escopo com cliente, será construída a EAP em conjunto com outros artefatos, como o protótipo, documento de visão. Após a finalização desses documentos, a equipe de gerência validará esses documentos, e caso não estejam consistentes com a definição do projeto, serão refeitos. Após essa primeira validação, será marcada uma reunião com o cliente a fim de apresentar e validar o projeto. Caso o cliente demande funcionalidades adicionais, e haja uma alteração no escopo, a EAP será replanejada.


## 3. Desenvolvimento e Manutenção da Estrutura Analítica do Projeto - EAP

O desenvolvimento da EAP será baseado nos requisitos necessários para o escopo do projeto. O projeto como um todo será dividido entre pacotes de atividades. Decidiu-se organizar esses pacotes seguindo uma ordem cronológica, dessa forma, o projeto será divido em duas Releases, sendo que a primeira será composta por três iterações do RUP (duas fases).

#### 3.1. Processo de definição do Escopo


O processo de definição do escopo consistirá de 4 atividades básicas:

1. Concepção de ideias para o projeto pelos envolvido

2. Especificar o escopo, ou seja, refinar as ideias anteriores, definindo quais pertencerão e quais não 
pertencerão ao escopo do projeto. Dessa forma, todos terão uma visão mais clara acerca do escopo do projeto.

3. Limitar o escopo baseando-se no tempo e recursos disponíveis e na qualidade desejada.

4. Aprovação do escopo pelos integrantes da gerência e pelo cliente


## 4. Desenvolvimento e Manutenção da Estrutura Analítica do Projeto - EAP

O desenvolvimento da EAP será baseado nos requisitos necessários para o escopo do projeto. O projeto como um todo será dividido entre pacotes de atividades. Decidiu-se organizar esses pacotes seguindo uma ordem cronológica, dessa forma, o projeto será divido em duas Releases, sendo que a primeira será composta por três iterações do RUP (abrangendo as duas primeiras fases).

O processo de Desenvolvimento da EAP pode ser observado pela figura abaixo:


Percebe-se que esse processo consiste das seguintes atividades:

**1. Coletar Requisitos:** Serão levantadas as funcionalidades interessantes para o sistema.

**2. Definir Escopo:** Será definido o que o sistema abrangerá ou não abrangerá.

**3. Estabelecer Entregas:** Será definido o que será entregue para o cliente que agregue valor a aplicação. Podem ser artefatos importantes para o cliente, funcionalidades da aplicação, treinamento para a utilização do sistema.

**4. Validar a EAP:** Após as etapas anteriores, a EAP será construída. Posteriormente, deve-se validá-la com o cliente. Caso validada, o processo se encerra, caso contrario, voltamos a atividade 1.

A manutenção da EAP, será tratada no tópico 5, porém é interessante ressaltar que após qualquer alteração de escopo, ela deverá ser revalidada. Essas alterações também impactarão o cronograma do projeto.

## 5. Gestão de Mudanças do Escopo


Conforme o que foi dito anteriormente nesse documento, nota-se que diversos fatores internos ou externos ao projeto podem impactar o escopo. Normalmente, ele é alterado para acomodar novas funcionalidades sugeridas pelo cliente. O fato de o escopo ser bastante volátil em diversos projeto, torna interessante a definição de um processo a ser seguido a cada mudança.

O processo de gestão de Mudanças de Escopo definido pode ser compreendido pela seguinte imagem. 


Esse processo é composto pelas seguintes atividades:

**1. Identificação da necessidade de mudança:** Será definido se aquela mudança é necessária ou não para o projeto. Independente necessidade da mudança ela não será descartada (pode não ser necessária, mas importante), esse passo é importante para futuramente avaliar se será aplicada. 

**2. Identificar possíveis alternativas a mudança desejada:** Talvez a mudança proposta não seja a melhor para o projeto. Dessa forma, é interessante analisar alternativas.

**3. Identificar a melhor alternativa:** É nessa etapa que será determinada a mudança a ser efetuada no escopo do projetom, utilizando como base as alternativas geradas pela atividade anterior.

**4. Analisar o impacto da mudança no projeto:** Serão levantados e avaliados os impactos da mudança proposta. Esses podem ser positivos ou negativos e sua análise será utilizada pela atividade que a segue.

**5. Validar a Mudança:** É aqui que será determinada se a mudança será ou não aplicada ao projeto. A equipe de gerência em conjunto com o cliente são os responsáveis pela validação. Caso não seja validada, volta-se para o passo 2. Caso positivo, o processo é finalizada. 


## 6. Referências Bibliográficas

* PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.