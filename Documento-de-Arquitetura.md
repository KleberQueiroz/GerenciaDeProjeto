# Documento de Arquitetura

## Histórico de Revisões

|      Data     | Versão | Descrição                                                                | Autor         |
|---------------|--------|--------------------------------------------------------------------------|---------------|
|  23/03/2017   |  1.0   | Iniciando documento de arquitetura do projeto.                           | Lucas S.      |
|  23/03/2017   |  1.1   | Introdução(Finalidade, Escopo)                                           | Lucas S.      |
|  23/03/2017   |  1.2   | Representação da Arquitetura                                             | Jordan        |
|  23/03/2017   |  1.3   | Tamanho e desempenho                                                     | Sannya Arvelos|
|  23/03/2017   |  1.4   | Visão de Casos de Uso(Atores)                                            | Lucas S.      |
|  23/03/2017   |  1.5   | Restrições e Metas Arquiteturais                                         | Sannya Arvelos|
|  23/03/2017   |  1.6   | Melhorias Representação da Arquitetura                                   | Sannya Arvelos|
|  23/03/2017   |  1.7   | Visão lógica                                                             | Lucas S.      |
|  23/03/2017   |  1.8   | Qualidade                                                                | Sannya Arvelos|
|  25/03/2017   |  1.9   | Atualizações de Metas Arquiteturais                                      | Jordan        |
|  30/03/2017   |  2.0   | Melhoria do Tópico de Qualidade                                          | Lucas S.      |


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
&nbsp;&nbsp;[5.1. Propósito](#51-diagrama-de-classes)  
&nbsp;&nbsp;[5.2. Propósito](#52-banco-de-dados)    
[6. Desempenho](#6desempenho)  
[7. Qualidade](#7-qualidade)  

-------------------------------------------------------------------

## 1) Introdução

### 1.1 Finalidade

<p align ="justify">A finalidade deste artefato é apresentar a arquitetura escolhida para a construção da aplicação web UnBMapa. Serão expostas as visões arquiteturais utilizadas, tendo como objetivo deixar de forma explícita as decisões estabelecidas.

### 1.2 Escopo  

<p align ="justify">Este documento foi construído sobre a visão arquitetural utilizada na implementação da UnBMapa. Serão expostas as visões arquiteturais utilizadas, tendo como objetivo deixar de forma explícita as decisões estabelecidas.
 
## 2) Representação da Arquitetura

<p align ="justify">A arquitetura utilizada na UnBMapa será o padrão MVC. Tal padrão possui três layers de trabalho Model-View-Controller. Cada layer desempenha uma função nesta arquitetura. A View, primeira camada, é responsável por exibir as informações sobre as rotas a serem tomadas, bem como mapas e afins. Havendo, assim, uma interação com o usuário. A model, segunda camada, é encarregada de armazenar as informações coletadas na view e a Controller é a responsável por manipular as entradas recebidas e fazer a comunicação entre as duas camadas anteriores.

## 3) Restrições e Metas Arquiteturais

### 3.1 Metas Arquiteturais  
	
	* O sistema tem como objetivo facilitar a localização do usuário no Campus Darcy Ribeiro. Facilitando o acesso por suas instalações.
	* O sistema contará com uma interface interativa com o usuário.
	* O sistema contará com uma interface responsiva.
	* O sistema contará com o recurso Bootstrap.
	* Deverá garantir uma boa estrutura e qualidade de código.

### 3.2 Restrições  
	
	* Será necessário que haja conexão com a internet.
	* O sistema dependerá dos dados físicos do Campus Darcy Ribeiro.
	* O sistema deverá ser atualizado de acordo com modificações no Campus Darcy Ribeiro.

## 4) Visão de Casos de Uso  

### 4.1 Atores

#### 4.1.1 Usuários

O ator usuário se refere a todas às pessoas que desejam se localizar dentro do Campus Darcy Ribeiro. Este tipo de ator poderá utilizar da maioria dos recursos do UnBMapa, exceto os de cunho administrativo. Como exemplo de funcionalidas que ele terá à sua disposição: Calcular distância entre edifícios, localizar edifícios, localizar pontos de alimentação, entre outras.

#### 4.1.2 Administradores

O ator administrador se refere às pessoas que manterão o sistema. Este tipo de ator poderá utilizar de todos os recursos do UnBMapa. Como por exemplo de funcionalidades exclusivas de administrador: Cadastrar edifício, cadastrar departamentos, entre outras.  

### 4.2 Diagrama de Casos de Uso

### 4.3 Descrição dos Casos de Uso

## 5) Visão Lógica

A aplicação é construída sobre o framework Rails utilizando a linguagem de alto nível Ruby. Estre framework utiliza a lógica MVC(Model-View-Controller), tal lógica permite a divisão da estrutura da ferramenta web em 3 blocos sólidos que comunicam-se entre si: View, controller, model.

### 5.1 View

View é o bloco responsável por tudo aquilo que o usuário pode ver em seu navegador. Responsável, também, por receber os estímulos fornecidos pelos usuários na aplicação. Como por exemplo, as telas, menus, botões, caixas de pesquisas, entre outros encontrados na aplicação.

### 5.2 Controller

Controller é o bloco responsável por fazer a comunicação entre a model e a view. Literalmente controlando os dados de camada à camada.

### 5.3 Model

Model é o bloco que tem como responsabilidade a transferência, manutenção e definição dos dados das classes escritas em Ruby para o Banco de Dados. Exemplos destes dados são: os edifícios, departamentos, salas, pontos de alimentação que serão cadastrados no sistema. Cada um destes grupo será descrito como uma classe na aplicação que servirá como molde para as entidades físicas cadastradas.

### 5.4 Diagrama de Classes

### 5.2 Banco de Dados

O framework Rails, antes citado deste documento, possui uma base de dados padrão em MySQL, entretanto, visando a quantidade de acessos simultâneos que os dados da aplicação podem possuir, decidiu-se que a base de dados seria trocada para uma descrita em PostgreSQL pois esta possui maior suporte a uma grande transferência de dados simultâneos.

## 6) Desempenho

O desempenho do site irá depender diretamente da conexão a internet do usuário. O sistema deverá garantir o ajuste de tela (bootstrap) para todos os dispositivos móveis, o que implicaria em um bom funcionamento da aplicação quando utilizada via smartphone.

## 7) Qualidade

De posse da explicação do funcionamento da arquitetura utilizada para a construção do sistema pode-se chegar a conclusão que o sistema ficará mais sólido dividido entre os três blocos, Model, View, Controller. A arquitetura permite, também, um significativo aumento na facilidade de manutenção do código pois existe um lugar para cada função. A linguagem utilizada no framework, Ruby, por ser de alto nível permite uma leitura mais fluida de todo o código o que também facilita no momento de manutenção deste sistema.