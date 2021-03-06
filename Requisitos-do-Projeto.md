## Histórico de Revisões
| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|03/04/2017|0.1|Criando estutura do documento|Rafael Rabetti|
|03/04/2017|1.0|Problemas, Necessidades,Características, Requisitos, Casos de uso e Rastreabilidade|Rafael Rabetti|
|07/04/2017|1.0|Refatorando casos de uso e rastreabilidade|Rafael Rabetti|
|19/04/2017|1.1|Refatorando casos de uso e rastreabilidade|Rafael Rabetti|
|19/04/2017|1.1|Refatorando casos de uso e rastreabilidade|Rafael Rabetti|
|19/04/2017|1.2|matriz de ratreabilidade|Eduardo Brasil|
***
## Sumário

1. [Problemas](#1-problemas)

2. [Necessidades](#2-necessidades)

3. [Características](#3-características)

4. [Requisitos](#4-requisitos)

5. [Casos de uso](#5-casos-de-uso)

6. [Matriz de rastreabilidade](#6-matriz-de-rastreabilidade)


### 1. Problemas

| ID | O problema de | afeta | cujo impacto é | Uma boa solução seria |
|----|---------------|-------|----------------|-----------------------|
| **P1** | A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro,  | estudantes, servidores e visitantes da universidade | a demora para encontrar e chegar à determinado lugar na universidade |  uma plataforma web que fornece as informações de localização de salas e prédios dentro do campus. |

### 2. Necessidades

| **ID**   | **Necessidade**     | **Descrição**|
|----------|-----------------|---------------|
|**NE01**|Orienteção dentro do campus|Atualmente, a localização dentro do campus conta apenas com marcações de teto que muitas vezes são de difícil visualização.|

### 3. Características

| **ID**   | **Característica**     | **Descrição**|
|----------|-----------------|---------------|
|**CA01**|Mapa com as principais localidades.| Apresentação da localização de salas e edifícios.|
|**CA02**|Orientação entre localidades| Apresentação de rotas e caminhos entre as principais localidades. |

### 4. Requisitos
| **ID**   | **Requisito**     | **Descrição**|
|----------|-----------------|---------------|
|**R01**|Localizar Edifícios|O sistema deve apresentar ao usuário a localização dos vários edifícios dentro do campus.|
|**R02**|Localizar Departamentos|O sistema deve apresentar ao usuário a localização dos vários departamentos dentro do campus.|
|**R03**|Localizar Salas|O sistema deve apresentar ao usuário a localização das salas dentro do campus.|
|**R04**|Localizar Bicicletários|O sistema deve apresentar ao usuário a localização dos bicicletários dentro do campus.|
|**R05**|Indicar trajetos entre locais|O sistema deve apresentar rotas, partindo da localização atual do usuário até o destino desejado.|
|**R06**|Informar sobre uma localidade|O sistema deve aprensentar informações sobre um determinado edifício, sala, departamento ou local de comida. Como, horário de funcionamento, nome e outras informações.|

### 5. Casos de Uso

O diagrama de casos de uso pode ser visto [aqui](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB/wiki/Diagrama-de-Casos-de-Uso).

| **ID**   | **Caso de Uso**     | **Descrição**|
|----------|-----------------|---------------|
|**UC01**|Manter Edifícios|Permite a criação, leitura, exclusão e alteração de edifícios.|
|**UC02**|Manter Departamentos|Permite a criação, leitura, exclusão e alteração de departamentos.|
|**UC03**|Manter Salas |Permite a criação, leitura, exclusão e alteração de salas.|
|**UC04**|Manter Bicicletários|Permite a criação, leitura, exclusão e alteração de bicicletários.|
|**UC05**|Manter Pontos de Acesso|Permite a criação, leitura, exclusão e alteração dos pontos de acesso de um edifício.|
|**UC06**|Mostrar Informações|Apresenta para o usuário informações sobre o local desejado. |
|**UC07**|Calcular Trajeto|Permite ao usuário, partindo da sua localização atual, traçar rotas para chegar a um destino desejado.|
|**UC08**|Pesquisar Locais do Campus|Permite ao usuário pesquisar locais dentro da universidade.|
|**UC09**|Mostrar Mapa do Campus|Destinado a mostrar ao usuário o mapa do campus.|
|**UC10**|Fazer Login|O caso de uso é destinado ao administrador para efetuar o login na aplicação.|
|**UC11**|Manter Administradores|O caso de uso é destinado ao administrador. Através dele é possível gerenciar as contas de administradores na aplicação.|

### 6. Rastreabilidade
![Imgur](http://i.imgur.com/hfcPX11.png)

[Clique aqui para visualizar melhor.](http://i.imgur.com/hfcPX11.png)


##### 6.1 matriz de rastreabilidade

Segundo o Guia PMBOK®, a matriz de rastreabilidade dos requisitos associa os requisitos às suas origens e os rastreia durante todo o ciclo de vida do projeto.

![Imgur](http://i.imgur.com/VkGe5Hu.png)