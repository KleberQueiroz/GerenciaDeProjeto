# Documento de Arquitetura

## Histórico de Revisões

| Data       | Versão | Descrição                                                                                                                                                                                                            | Autor                            |
|------------|--------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------|
| 23/03/201  | 0.1    | Iniciando documento de arquitetura do projeto.                                                                                                                                                                       | Lucas S.                         |
| 23/03/201  | 0.2    | Introdução(Finalidade, Escopo);  Representação da Arquitetura;Tamanho e desempenho; Visão de Casos de Uso(Atores); Restrições e Metas Arquiteturais; Revisão da Representação da Arquitetura; Visão LógicaQualidade; | Jordan, Lucas S., Sannya Arvelos |
| 25/03/2017 | 1.0    | Atualização de Metas Arquiteturais                                                                                                                                                                                   | Jordan                           |
| 30/03/2017 | 1.1    | Melhoria do tópico de qualidade; Descrição dos casos de uso; Correção das Descrições de Casos de Uso;                                                                                                                | Lucas S.                         |
| 01/04/2017 | 1.2    | Atualização de Representação da Arquitetura                                                                                                                                                                          | Jordan                           |
| 03/04/2017 | 1.3    | Correção da Visão Lógica                                                                                                                                                                                             | Lucas S.                         |
| 04/04/2017 | 1.4    | Refatoração Representação da Arquitetura; Refatoração Metas e Restrições Arquitetura; Refatoração Banco de Dados; Refatoração Desempenho; Refatoração Qualidade;                                                     | Kairon Velozo                    |
| 06/04/2017 | 1.5    | Atualização dos casos de uso e do seu diagramas                                                                                                                                                                      | Mateus Roriz                     |
| 07/04/2017 | 1.6    | Atualização do diagrama de pacotes e diagrama de classe                                                                                                                                                              | Mateus Roriz                     |


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

<p align ="justify">A finalidade deste artefato é apresentar a arquitetura escolhida para a construção da aplicação Onde É? UnB. Serão expostas as visões arquiteturais utilizadas, tendo como objetivo deixar de forma explícita as decisões estabelecidas.    

### 1.2 Escopo  

<p align ="justify">Este documento foi construído sobre a visão arquitetural utilizada na implementação da Onde É? UnB. Serão expostas as visões arquiteturais utilizadas, tendo como objetivo deixar de forma explícita as decisões estabelecidas.   
 
## 2) Representação da Arquitetura   

<p align ="justify">A arquitetura utilizada na aplicação é o padrão arquitetural Model-View-Controller (MVC), que é adotada framework Ruby on Rails.   

<p align ="justify">Model - A camada model é responsável pela regras de negócio da aplicação e a as regras para manipulação de dados. Esta representa as informações abstraídas do mundo real definindo como tais informações são armazenadas no banco de dados e suas relações desempenhadas.    

<p align ="justify">View - A camada view é a responsável por formatar as informações e apresentá-las ao usuário de forma organizada.   

<p align ="justify">Controller - A camada controller é responsável pelo fluxo do usuário na aplicação. Esta é usada para comunicação com a Model e renderização das Views, com informações procedentes da Model.   

![](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2017.1-LocalizacaoDarcy/imagens/diagrama-mvc.png)  
[Diagrama da Lógica MVC](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2017.1-LocalizacaoDarcy/imagens/diagrama-mvc.png)   

<p align ="justify">O diagrama pode ser descrito da seguinte maneira:

<p align ="justify">1 - O usuário deseja acessar uma página da aplicação através do browser. O browser envia a solicitação ao servidor e, através do gerenciador de rotas do Rails, a solicitação é enviada à uma Controller.   

<p align ="justify">2 - Caso a página que o usuário deseja observar tenha alguma informação que necessite ser puxada da base de dados, a Controller irá solicitar a uma Model.   

<p align ="justify">3 - A Model solicitará as informações a base de dados.    

<p align ="justify">4 - As informações são retornadas a Model. Nesse momento os dados são tratados de forma a seguir as regras de negócio da aplicação.    

<p align ="justify">5 - A Model retorna as informações a Controller.   

<p align ="justify">6 - A Controller envia as informações solicitadas para a View, para que estas sejam formatadas.   

<p align ="justify">7 - A View formata as informações recebidas e retorna ao usuário.   

## 3) Restrições e Metas Arquiteturais  

<p align ="justify">O Ruby on Rails possui uma série de princípios e convenções que auxiliarão na tomada de decisões no que se refere ao desenvolvimento. Tais recursos do framework poderão auxiliar no rápido desenvolvimento e na manutenibilidade da aplicação.    
<p align ="justify">A aplicação adotará as práticas de segurança sugeridas nos guias do framework Ruby on Rails. Dados sensitivos tais como senhas dos administradores são guardados criptografados. O gerenciamento das informações que o usuário terá acesso publicamente é feito apenas por administradores.   
<p align ="justify">Além disso, a arquitetura adotada permitirá que a equipe de desenvolvimento possa trabalhar nas camadas separadamente. Isso tem como consequência desacoplamento e a melhora para desenvolvimento de testes.  
<p align ="justify">Uma restrição identificada é que o funcionamento da aplicação dependerá de o usuário estar conectado à internet. Não sendo possível, de forma alguma, o seu funcionamento offline.   

## 4) Visão de Casos de Uso   

### 4.1 Atores   

#### 4.1.1 Usuários   

<p align ="justify">O ator usuário se refere a todas às pessoas que desejam utilizar a aplicação, tendo acesso, unicamente, às funcionalidades disponibilizadas de forma pública.    

#### 4.1.2 Administradores

<p align ="justify">O ator administrador se refere às pessoas que serão responsáveis pela manutenibilidade das informações de interesse público da aplicação. Este ator também é considerado um usuário, pois pode também usufruir de todos os recursos oferecidos.   

### 4.2 Diagrama de Casos de Uso   

![](http://i.imgur.com/UTJq5h0.png)  
[Diagrama de Casos de Uso 2.0](http://i.imgur.com/UTJq5h0.pngg)    

### 4.3 Descrição dos Casos de Uso  

**UC01 - Manter Edifícios** 
<p align ="justify">Este caso de uso se refere ao cadastro, atualização e destruição do objeto edifício no sistema.  

**UC02 - Manter Departamentos**  
<p align ="justify">Este caso de uso se refere ao cadastro,  atualização e destruição do objeto departamento no sistema.  

**UC03 - Manter Salas**  
<p align ="justify">Este caso de uso se refere ao cadastro, leitura, atualização e destruição do objeto edifício no sistema.  

**UC04 - Manter Bicicletários**  
<p align ="justify">Este caso de uso se refere ao cadastro,  atualização e destruição do objeto bicicletário no sistema.  

**UC05 - Manter Pontos de Acesso**  
<p align ="justify">Este caso de uso se refere ao cadastro, atualização e destruição do objeto ponto de acesso no sistema.  

**UC06 - Visualizar Informações**  
<p align ="justify">Este caso de uso se refere a visualização das informações sobre os pontos cadastrados no mapa, pelo usuário quando este clica em um dos itens expostos no mapa.   

**UC07 - Visualizar Trajeto**  
<p align ="justify">Este caso de uso se refere ao cálculo do trajeto entre edifícios no mapa do campus  após escolhidos pelo usuário.   

**UC08 - Procurar Locais no Campus**  
<p align ="justify">Este caso de uso se refere a pesquisa por um local no mapa da universidade após escolhido pelo usuário.  

**UC09 - Visualizar Mapa do Campus**  
<p align ="justify">Este caso de uso se refere ao ato de mostrar o mapa do Campus junto com os itens nele cadastrados ao usuário.  

## 5) Visão Lógica  

<p align ="justify">A aplicação Onde É? UnB é construída sobre o framework Rails utilizando a linguagem de alto nível Ruby. Este framework utiliza a lógica MVC(Model-View-Controller), tal lógica permite a divisão da estrutura da ferramenta web em 3 blocos sólidos que comunicam-se entre si: View, controller, model.     

### 5.1 Visão Geral

<p align ="justify">A lógica MVC trabalha da seguinte maneira: No momento em que o usuário faz uma requisição no seu navegador a View manda este pedido para a Controller. A Controller, por sua vez, interpreta tal evento e procura os dados necessários na Model para que estes sejam validados. Após os dados serem validados a Controller seleciona os necessários e responde a requisição da View que os transfere ao navegador do usuário.      

5.1.1 View


<p align ="justify">A View é responsável por tudo aquilo que o usuário pode ver em seu navegador. Responsável, também, por receber os estímulos fornecidos pelos usuários na aplicação. Como por exemplo, as telas, menus, botões, caixas de pesquisas, entre outros encontrados no sistema.    

5.1.2 Controller  

<p align ="justify">A Controller é responsável por fazer a comunicação entre as requisições recebidas pela View e os dados tratados pela Model, servido assim, de ponte entre elas. Por exemplo, no momento em que o view faz uma requisição, a controller processa este evento e opera os dados estão que contidos na Model validando-os para então responder a requisição à View.   

5.1.3 Model  

<p align ="justify">A Model é responsável por conter os dados da aplicação e quando necessário, os dados do database. Trata a escrita, a validação e a leitura de tais dados. Quando requisitada pela Controller, fornece os dados contidos para que a Controller decida exibi-los ou não na View.  

### 5.2 Diagrama de Classes  
<p align ="justify">Abaixo encontra-se o diagrama de classes do sistema:  

![](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2017.1-LocalizacaoDarcy/imagens/diagrama-de-classe-3.0.jpg)  
[Diagrama de Classes](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2017.1-LocalizacaoDarcy/imagens/diagrama-de-classe-3.0.jpg)  

### 5.3 Diagrama de Pacotes

![](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2017.1-LocalizacaoDarcy/imagens/diagrama-de-pacotes.png)  
[Diagrama de Pacotes](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2017.1-LocalizacaoDarcy/imagens/diagrama-de-pacotes.png)    

<p align ="justify"> 1.A camada de View é responsável pelo front-end do projeto, onde o usuário interage com a aplicação . A comunicação acontece através da Controller conforme for requisitado.

<p align ="justify"> 2.A camada Controller trata do processamento de cada ação do sistema. Ela pode ser entendida como a camada que faz a comunicação entre a Model e a View, ela compreende os eventos que estão acontecendo na View, e atua sobre os dados da Model, estabelecendo assim a comunicação com a database que armazena esses dados no banco.

<p align ="justify"> 3.A camada  Model armazena os dados da aplicação se necessário e trata da leitura e validação dos dado  se comunica com a Controller quando existir a necessidade de exibição, e a Controller vai decidir em qual das view exibir os dados da Model.

<p align ="justify"> 4.A camada de Tests serve como uma ambiente para validação da aplicação antes que as alterações feitas neles sejam implementadas nas outras branchs.



### 5.4 Banco de Dados

<p align ="justify">O projeto utiliza o sistema gerenciamento de banco de dados SQLite3 para o ambiente de desenvolvimento. No ambiente de produção é utilizado outro sistema de banco de dados, o PostgreSQL.  
<p align ="justify">O PostgreSQL foi adotado em ambiente de produção devido a possibilidade para trabalhar de maneira eficiente com dados geolocalizados.  

## 6) Desempenho

<p align ="justify">Serão adotadas práticas para que a aplicação tenha bom desempenho no navegador do usuário.   
<p align ="justify">Os dados do mapa serão mostrados por demanda, de acordo com a interação do usuário. Estes dados virão em formato JSON (JavaScript Object Notation) e serão carregados apenas quando necessários. A necessidade do carregamento dos dados será definida por uma série de lógicas que serão implementadas.   
<p align ="justify">Arquivos do tipo CSS e JavaScript passarão por processos de compressão e minificação para que possam ser carregados rapidamente.   
<p align ="justify">Além disso, o sistema de cache disponíveis nos navegadores auxiliarão no desempenho da aplicação.    

## 7) Qualidade  

<p align ="justify">Os padrões adotados no projeto seguirão convenções do framework Ruby on Rails, e são amplamente utilizadas por projetos de diversos tamanhos. Além disso, os desenvolvedores farão uso das folhas de estilo das linguagens utilizadas no projeto, auxiliando dessa forma, que o projeto seja desenvolvido com qualidade satisfatória, adotando boas práticas de desenvolvimento.  