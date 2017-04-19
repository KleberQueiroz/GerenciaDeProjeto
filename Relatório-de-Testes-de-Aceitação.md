## Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|19/04/2017|0.1|Criação do documento|Alexandre Torres Kryonidis|
***

## Sumário

1. [Introdução](#1-introdução)

2. [Sobre os testes](#2-sobre-testes)

3. [Problemas](#3-problemas)

4. [Tentativas de solucionar o problema](#4-tentativas-solucionar-problema)

5. [Resultados](#5-resultados)



## 1. Introdução

## 2. Sobre os testes

Foi utilizada principalmente a gem ‘cucumber’ para a realização dos testes de aceitação.

Foram testadas as seguintes features. Os cenários delas podem ser vistas na pasta 'features' do repositório.

1)
	* Feature: View Unb Map
	In order find a specific location 
	As a normal user
	I want to view the university map

2)
	* Feature: View about page
	In order find information about the project
	As a normal user
	I want to view the about page

3)
	* Feature: Manage the web application content
	In order to manage the website content
	As an admin user
	I want to interact with the admin dashboard



## 3. Problemas

Todo o conteúdo HTML presente na pasta ‘app/views’ pode ser testada normalmente utilizando o cucumber. Ou seja, o cucumber consegue encontrar todas as tags e conteúdo html.

O problema ocorreu ao testar o código gerado dinamicamente pela API leaflet, via javascript. O mapa e botões como o de zoom, que vemos na tela principal por exemplo, é gerado via javascript. E, por isso, o cucumber não consegue encontrar esses elementos na DOM do HTML.

Dessa forma, não conseguimos rodar os testes que englobam conteúdo gerado dinamicamente.

## 4. Tentativas de solucionar o problema

1. Passamos a utilizar, então, o "Capybara". Porém o seu driver padrão "RackTest" também não tem suporte a javascript.

2. Então, tentou-se utilizar o "Capybara" com o driver do "selenium". Apesar de termos configurado o ambiente corretamente e instalado o firefox, geckodriver e o selenium, essa solução não foi viável. Isso porque o grupo está usando vagrant, e a falta de uma GUI impede a sua utilização.

3. Finalmente, encontrou-se um browser que não depende de uma interface gráfica, o PhantomJS que em conjunto com o driver "poltergeist" para o Capybara, em teoria, solucionaria o nosso problema. Porém, ele também não funcionou, ou não conseguimos configurá-lo corretamente.

## 5. Resultados

O numero de testes ficou reduzido devido aos problemas citados, mas o resultado obtido foi o seguinte:


	9 scenarios (9 passed)
	32 steps (32 passed)
	0m3.257s