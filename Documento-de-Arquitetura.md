# Documento de Arquitetura

## Histórico de Revisões

|      Data     | Versão | Descrição                                                                | Autor         |
|---------------|--------|--------------------------------------------------------------------------|---------------|
|  23/03/2017   |  1.00   | Iniciando documento de arquitetura do projeto.                           | Lucas S.      |
|  23/03/2017   |  1.10   | Introdução(Finalidade, Escopo)                                           | Lucas S.      |
|  23/03/2017   |  1.20   | Representação da Arquitetura                                             | Jordan        |
|  23/03/2017   |  1.30   | Tamanho e desempenho                                                     | Sannya Arvelos|
|  23/03/2017   |  1.40   | Visão de Casos de Uso(Atores)                                            | Lucas S.      |
|  23/03/2017   |  1.50   | Restrições e Metas Arquiteturais                                         | Sannya Arvelos|
|  23/03/2017   |  1.60   | Melhorias Representação da Arquitetura                                   | Sannya Arvelos|
|  23/03/2017   |  1.70   | Visão lógica                                                             | Lucas S.      |
|  23/03/2017   |  1.80   | Qualidade                                                                | Sannya Arvelos|
|  25/03/2017   |  1.90   | Atualizações de Metas Arquiteturais                                      | Jordan        |
|  30/03/2017   |  2.00   | Melhoria do Tópico de Qualidade                                          | Lucas S.      |
|  30/03/2017   |  2.10   | Descrição dos Casos de Uso                                               | Lucas S.      |
|  30/03/2017   |  2.15   | Correção das Descrições dos Casos de Uso                                 | Lucas S.      |
|  01/04/2017   |  2.20   | Atualização de Representação da Arquitetura                              | Jordan        |
|  03/04/2017   |  2.30   | Correção da Visão Lógica                                                 | Lucas S.      |


-------------------------------------------------------------------

## Sumário

[1. Introdução](#1-introdução)  
&nbsp;&nbsp;[1.1. Finalidade](#11-finalidade)  
&nbsp;&nbsp;[1.2. Escopo](#12-escopo)  
[2. Representação da Arquitetura](#2-representação-da-arquitetura)  
[3. Restrições e Metas Arquiteturais](#3-restrições-e-metas-arquiteturais)  
[4. Visão de Casos de Uso](#4-visão-de-casos-de-uso)  
&nbsp;&nbsp;[4.1. Atores](#41-atores)  
&nbsp;&nbsp;[4.2. Diagrama de Casos de Uso](#42-diagrama-de-casos-de-uso)  
&nbsp;&nbsp;[4.3. Descrição dos Casos de Uso](#43-descrição-dos-casos-de-uso)    
[5. Visão Lógica](#5-visão-lógica)  
&nbsp;&nbsp;[5.1. Visão Geral](#51-visão-geral)  
&nbsp;&nbsp;[5.2. Diagrama de Classes](#52-diagrama-de-classes)  
&nbsp;&nbsp;[5.3. Diagrama de Pacotes](#53-diagrama-de-pacotes)  
&nbsp;&nbsp;[5.4. Banco de Dados](#54-banco-de-dados)    
[6. Desempenho](#6desempenho)  
[7. Qualidade](#7-qualidade)  

-------------------------------------------------------------------

## 1) Introdução

### 1.1 Finalidade

<p align ="justify">A finalidade deste artefato é apresentar a arquitetura escolhida para a construção da aplicação web UnBMapa. Serão expostas as visões arquiteturais utilizadas, tendo como objetivo deixar de forma explícita as decisões estabelecidas.

### 1.2 Escopo  

<p align ="justify">Este documento foi construído sobre a visão arquitetural utilizada na implementação da UnBMapa. Serão expostas as visões arquiteturais utilizadas, tendo como objetivo deixar de forma explícita as decisões estabelecidas.
 
## 2) Representação da Arquitetura

<p align ="justify">A arquitetura utilizada na ‘Onde É a UnB?’ será o padrão MVC. Tal padrão possui três grupos de trabalho Model-View-Controller. Cada grupo desempenha uma função nesta arquitetura. A View é responsável por exibir as informações sobre as rotas a serem tomadas, bem como mapas e afins. Havendo, assim, uma interação com o usuário. A Model é encarregada de armazenar as informações coletadas na view e a Controller é a responsável por manipular as entradas recebidas e fazer a comunicação entre as duas camadas anteriores.

## 3) Restrições e Metas Arquiteturais

<p align ="justify"> * A aplicação web 'Onde É a UnB?' será desenvolvida utilizando o framework Ruby on Rails. Tal framework é escrito utilizando a linguagem Ruby e é baseado no padrão de arquitetura MVC (Model-View-Controller).

<p align ="justify"> * O banco de dados padrão do Ruby on Rails é o SQLite3, entretanto, decidiu-se que o banco utilizado será o Postegree, pois tal banco possui a possibilidade de se utilizar dados de geolocalização.

## 4) Visão de Casos de Uso  

### 4.1 Atores

#### 4.1.1 Usuários

<p align ="justify">O ator usuário se refere a todas às pessoas que desejam se localizar dentro do Campus Darcy Ribeiro. Este tipo de ator poderá utilizar da maioria dos recursos do UnBMapa, exceto os de cunho administrativo. Como exemplo de funcionalidas que ele terá à sua disposição: Calcular distância entre edifícios, localizar edifícios, localizar pontos de alimentação, entre outras.

#### 4.1.2 Administradores

<p align ="justify">O ator administrador se refere às pessoas que manterão o sistema. Este tipo de ator poderá utilizar de todos os recursos do UnBMapa. Como por exemplo de funcionalidades exclusivas de administrador: Cadastrar edifício, cadastrar departamentos, entre outras.  

### 4.2 Diagrama de Casos de Uso

### 4.3 Descrição dos Casos de Uso

**UC01 - Manter Administrador** 
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto administrador no sistema.  

**UC02 - Manter Edifícios**  
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto edifício no sistema.  

**UC03 - Manter Departamentos**  
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto edifício no sistema.  

**UC04 - Manter Salas**  
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto sala no sistema.  

**UC05 - Manter Centros Acadêmicos** 
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto centro acadêmico no sistema.  

**UC06 - Manter Bicicletários**  
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto bicicletário no sistema.  

**UC07 - Manter Pontos de Acesso**  
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto ponto de acesso no sistema. 

**UC08 - Mostrar informações**  
<p align ="justify">Este caso de uso se refere ao momento em que o usuário clica em um dos itens expostos no mapa e o sistema retorna as informações deste item.

**UC09 - Calcular Trajeto entre Edifícios**  
<p align ="justify">Este caso de uso se refere a ação de após escolhidos dois pontos no mapa o sistema calcular a distancia entre eles.

**UC10 - Procurar Locais no Campus**  
<p align ="justify">Este caso de uso se refere a ação de procura de um local desejado que já foi cadastrado no sistema.

**UC11 - Mostrar Mapa do Campus**  
<p align ="justify">Este caso de uso se refere ao ato de mostrar o mapa do Campus junto com os itens nele cadastrados.



## 5) Visão Lógica

<p align ="justify">A aplicação 'Onde É a UnB' é construída sobre o framework Rails utilizando a linguagem de alto nível Ruby. Estre framework utiliza a lógica MVC(Model-View-Controller), tal lógica permite a divisão da estrutura da ferramenta web em 3 blocos sólidos que comunicam-se entre si: View, controller, model.  

### 5.1 Visão Geral

<p align ="justify">A lógica MVC trabalha da seguinte maneira: No momento em que o usuário faz uma requisição no seu navegador a View manda este pedido à Controller. A Controller, por sua vez, interpreta tal evento e procura os dados necessários na Model para que estes sejam validados. Após os dados serem validados a Controller seleciona os necessários e responde a requisição da View que os transfere ao navegador do usuário.  

5.1.1 View


<p align ="justify">A View é responsável por tudo aquilo que o usuário pode ver em seu navegador. Responsável, também, por receber os estímulos fornecidos pelos usuários na aplicação. Como por exemplo, as telas, menus, botões, caixas de pesquisas, entre outros encontrados no sistema.

5.1.2 Controller

<p align ="justify">A Controller é responsável por fazer a comunicação entre as requisições recebidas pela View e os dados tratados pela Model, servido assim, de ponte entre elas. Por exemplo, no momento em que o view faz uma requisição, a controller processa este evento e opera os dados estão que contidos na Model validando-os para então responder a requisição à View.  

5.1.3 Model

<p align ="justify">A Model é responsável por conter os dados da aplicação. Trata a escrita, a validação e a leitura de tais dados. Sendo responsável, também, por conter, quando necessário, os dados no database. Quando requisitada pela Controller, fornece os dados contidos para que a Controller decida exibi-los ou não na View.

### 5.2 Diagrama de Classes

### 5.3 Diagrama de Pacotes

### 5.4 Banco de Dados

<p align ="justify">O framework Rails, antes citado neste documento, possui uma base de dados padrão em MySQL, entretanto, foi acordado que o banco de dados seria descrito em Postegree pois esta linguagem possui suporte a dados de geolocalização. Facilitando, assim, o processo de construção das funções de localização na aplicação.

## 6) Desempenho

<p align ="justify">O desempenho do site irá depender diretamente da conexão a internet do usuário. O sistema deverá garantir o ajuste de tela (bootstrap) para todos os dispositivos móveis, o que implicaria em um bom funcionamento da aplicação quando utilizada via smartphone.

## 7) Qualidade

<p align ="justify">De posse da explicação do funcionamento da arquitetura utilizada para a construção do sistema pode-se chegar a conclusão que o sistema ficará mais sólido dividido entre os três blocos, Model, View, Controller. A arquitetura permite, também, um significativo aumento na facilidade de manutenção do código pois existe um lugar para cada função. A linguagem utilizada no framework, Ruby, por ser de alto nível permite uma leitura mais fluida de todo o código o que também facilita no momento de manutenção deste sistema.