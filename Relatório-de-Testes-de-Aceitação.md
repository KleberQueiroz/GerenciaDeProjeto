Foi utilizada a gem ‘cucumber’ para a realização dos testes de aceitação.

1) Sobre os testes


Foram testadas as seguintes features. Os cenários delas podem ser vistas na pasta 'features' do repositório.

* Feature: View Unb Map
	In order find a specific location 
	As a normal user
	I want to view the university map

* Feature: View about page
	In order find information about the project
	As a normal user
	I want to view the about page

* Feature: Manage the web application content
	In order to manage the website content
	As an admin user
	I want to interact with the admin dashboard



2) Problema:

Todo o conteúdo HTML presente na pasta ‘app/views’ pode ser testada normalmente utilizando o cucumber. Ou seja, é possível encontrar todas as tags e conteúdo html.

O problema ocorreu ao testar o código gerado dinamicamente, via javascript, pela API leaflet. O mapa e botões como o de zoom, que vemos na tela principal, é gerado via javascript, e o cucumber não consegue encontrar esses elementos na DOM do HTML.

Dessa forma, não conseguimos rodar os testes que englobam conteúdo gerado dinamicamente.

3) Tentativas de solução do problema

Passamos a utilizar, então, o ‘Capybara’, porém o seu driver padrão ‘'RackTest" também não tem suporte a javascript.
Então, tentou-se utilizar o “capybara" com o driver do selenium. Apesar de termos configurado o ambiente corretamente e instalado o firefox, geckodriver e o selenium, essa solução não foi viável. Isso porque o grupo está usando vagrant, e a falta de uma GUI impede a sua utilização.
Finalmente, encontrou-se um browser que não depende de uma interface gráfica, o PhantomJS que em conjunto com o driver ‘poltergeist' para o Capybara, em teoria, solucionaria o nosso problema. Porém, ele também não funcionou, ou não conseguimos configurá-lo corretamente.

4) Resultado.

O numero de testes ficou reduzido devido aos problemas citados, mas o resultado obtido foi o seguinte:
9 scenarios (9 passed)
32 steps (32 passed)
0m3.257s