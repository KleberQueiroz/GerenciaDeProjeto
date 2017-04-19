## Histórico de Revisões

| Data  | Versão  |  Descrição | Autor  |
|---|:---:|---|---:|
|  18/04/2017 | 0.1  |  Início do Documento | Stéfane Souza  |
| 18/04/2017  | 0.2  |  Inclusão de TC10, TC06, TC07 | Stéfane Souza |
| 18/04/2017  | 1.0  | Inclusão de TC01, TC09 | Kairon Velozo  |


## TC01 - Cadastrar/Editar Edifícios 
## Classes de Equivalência 

| Caso de Teste  | Entrada  | Classes de Equivalência Válidas  | Classes de Equivalência Inválidas  |
|:-:|---|---|---|
| TC01 | Acrônimo (string)  | Caracteres do alfabeto ou números, com limite máximo de 20 caracteres.  | Caracteres especiais, strings com mais de 20 caracteres ou sem preenchimento.  |
| TC01  | Nome (string)  | Caracteres do alfabeto ou números, com limite máximo de 50 caracteres, sendo permitido o uso de “-”, “/”.  |  Caracteres especiais, strings com mais de 50 caracteres ou sem preenchimento. |
| TC01  | Telefone(inteiro)  | Números com até 11 dígitos.  | Caracteres especiais ou do alfabeto, números com mais de 11 dígitos ou menos de 10 dígitos e espaços em branco.  |
| TC01 |  Latitude (decimal) | Número decimal ou inteiro  | Caracteres especiais ou do alfabeto, espaços em branco.  |
| TC01  | Longitude(decimal)  |  Número decimal ou inteiro | Caracteres especiais ou do alfabeto, espaços em branco ou sem preenchimento.  |
| TC01  | GeoData (JSON)  | String no formato JSON.  | Strings sem estar no formato JSON ou estando mesmo que incorretamente.  |

## Análise de Resultados

| Caso de Teste  | Entrada  | Resultado esperado  | Resultado obtido  | Status  |
|:-:|---|---|---|---|
|  TC01_01 |  Acrônimo Válido  | O acrônimo é cadastrado no banco de dados  |  Acrônimo cadastrado | Êxito  |
| TC01_02  | Acrônimo inválido   | O sistema irá mostrar que o acrônimo inserido é inválido e solicita o dado novamente  |  Uma mensagem de erro de acrônimo inválido | Êxito  |
|  TC01_01 |  Nome Válido | O nome é cadastrado no banco de dados  | Nome cadastrado  | Êxito  |
| TC01_02  | Nome Inválido  |  O sistema irá mostrar que o nome inserido é inválido e solicita o dado novamente | Uma mensagem de erro de nome inválido  | Êxito  |
| TC01_01  | Telefone Válido  | O telefone é cadastrado no banco de dados  | Telefone cadastrado  | Êxito  |
| TC01_02  | Telefone Inválido  | O sistema irá mostrar que o telefone inserido é inválido e solicita o dado novamente  | Uma mensagem de erro de telefone inválido  | Êxito  |
| TC01_01  | Latitude Válida  | A latitude é cadastrada no banco de dados  | Latitude cadastrada  | Êxito  |
| TC01_02  | Latitude Inválido  | O sistema irá mostra que o formato da latitude é inválido e solicita o dado novamente  | Uma mensagem de erro de latitude inválida  | Êxito  |
| TC01_01  | Longitude Válida  | A longitude é cadastrada no banco de dados  | Longitude cadastrada  | Êxito|
| TC01_01  | GeoData Válida  | GeoData é cadastrada no banco de dados  | GeoData cadastrada  | Êxito  |
|  TC01_02 | GeoData Inválida  | O sistema irá mostra que o formato de GeoData é inválido e solicita o dado novamente  | Uma mensagem de erro de GeoData inválida  | Êxito  |


## TFUC06 - Visualizar Informações 
## Classes de Equivalência

| Caso de Teste  | Entrada  | Classes de Equivalência Válidas  | Classes de Equivalência Inválidas  |
|:-:|---|---|---|
| TC06  | Clique do usuário  | Não se aplica | Não se aplica  |

## Análise de Resultados

| Caso de Teste  | Entrada  | Resultado esperado  | Resultado obtido  | Status  |
|:-:|---|---|---|---|
| TC06_01  | Clique do usuário em um ponto do mapa  | O sistema irá mostrar uma janela com as informações do ponto clicado  | Informações do ponto clicado no mapa  | Êxito  |
| TC06_02  | Informações  |O sistema irá apresentar sigla, nome e telefone para o usuário   | Informações apresentadas no mapa  | Êxito  |

TFUC07 - Visualizar Trajeto
## Classes de Equivalência

| Caso de Teste  | Entrada  | Classes de Equivalência Válidas  | Classes de Equivalência Inválidas  |
|:-:|---|---|---|
| TC07  | Seleção do ponto de partida  | Não se aplica  | Não se aplica  |
| TC07  | Seleção do ponto de chegada  | Não se aplica  | Não se aplica  |
| TC07  | Apresentação do Trajeto  | Não se aplica  | Não se aplica  |

## Análise de Resultados

| Caso de Teste  | Entrada  | Resultado esperado  | Resultado obtido  | Status  |
|:-:|---|---|---|---|
| TC07_01  | Apresentação do Trajeto  | O sistema irá apresentar o trajeto no mapa entre os pontos selecionados  |  Trajeto apresentado na mapa |  Êxito |


TFUC09 - Visualizar Mapa 
## Classes de Equivalência

| Caso de Teste  | Entrada  | Classes de Equivalência Válidas  | Classes de Equivalência Inválidas  |
|:-:|---|---|---|
|  TC09 | Não se aplica.  | O mapa é apresentado ao usuário.  | Alguma mensagem de erro é apresentada ao usuário.  |

## Análise de Resultados

| Caso de Teste  | Entrada  | Resultado esperado  | Resultado obtido  | Status  |
|:-:|---|---|---|---|
| TC09_01  | Não se aplica.  | O mapa é apresentado.  | O mapa é apresentado  |  Êxito |



TFUC10 - Fazer Login 
## Classes de Equivalência

| Caso de Teste  | Entrada  | Classes de Equivalência Válidas  | Classes de Equivalência Inválidas  |
|:-:|---|---|---|
| TC10  | E-mail (string)  | E-mail com até 255 caracteres e é permitido o uso de “_”, “-”, “.”, “@”  | E-mail com mais de 255 caracteres, espaços em branco, outros caracteres não listados ou e-mail fora do padrão.|
| TC10  | Senha (inteiro)  | Senha com no mínimo 6 caracteres  | Senha com menos de 6 caracteres, caracteres especiais, espaços em branco  |

## Análise de Resultados

| Caso de Teste  | Entrada  | Resultado esperado  | Resultado obtido  | Status  |
|:-:|---|---|---|---|
| TC10_01  | E-mail Válido  | O administrador é logado.  | O admininstrador é logado.   | Êxito  |
| TC10_02  | E-mail Inválido  | O sistema irá mostrar os dados de acesso são incorretos.  | Uma mensagem de erro de dados incorretos.  | Êxito  |
| TC10_01  | Senha Válida  |  O admininstrador é logado.  | O admininstrador é logado.   |  Êxito |
| TC10_02  | Senha Inválida  | O sistema irá mostrar os dados de acesso são incorretos.  | Uma mensagem de erro de dados incorretos.  | Êxito  |
