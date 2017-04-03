## Histórico de Revisões
| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|22/03/2017|1.0|Criando estutura do documento|Rafael Rabetti|

***
## Sumário

1. [Problemas](#1-problemas)

2. [Necessidades](#2-necessidades)

3. [Características](#3-características)

4. [Requisitos](#4-requisitos)

5. [Casos de uso](#5-casos-de-uso)

6. [Matriz de rastreabilidade](#6-matriz-de-rastreabilidade)


### 1. Problemas

| **ID**   | **Problema**     | **Descrição**|
|----------|-----------------|---------------|
| **P01** | Dificuldade de localização |A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro afeta estudantes, servidores e visitantes da universidade, cujo impacto é a demora para encontrar e chegar à determinado lugar na universidade, causando atrasos.|

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
|**R04**|Localizar locais de alimentação|O sistema deve apresentar ao usuário a localização dos locais de alimentação dentro do campus.|
|**R05**|Localizar centros acadêmicos|O sistema deve apresentar ao usuário a localização dos centros acadêmicos dentro do campus.|
|**R06**|Indicar trajetos entre locais|O sistema deve apresentar rotas, partindo da localização atual do usuário até o destino desejado.|

### 5. Casos de Uso

| **ID**   | **Caso de Uso**     | **Descrição**|
|----------|-----------------|---------------|
|**UC01**|Manter Edifícios|Permite a criação, leitura, exclusão e alteração de edifícios.|
|**UC02**|Manter Salas|Permite a criação, leitura, exclusão e alteração de salas.|
|**UC03**|Manter Departamentos|Permite a criação, leitura, exclusão e alteração de departamentos.|
|**UC04**|Manter Centros Acadêmicos|Permite a criação, leitura, exclusão e alteração de centros acadêmicos.|
|**UC05**|Visualizar Informações Sobre Edifício|Apresenta para o usuário qual o nome do edifício e quais departamentos e salas estão ali dentro. |
|**UC06**|Pesquisar Edifícios|Permite ao usuário a busca um edifício a fim de saber a sua localização.|
|**UC07**|Pesquisar Sala|Permite ao usuário a busca uma sala a fim de saber a sua localização.|
|**UC08**|Pesquisar Departamento|Permite ao usuário a busca um departamento a fim de saber a sua localização.|
|**UC09**|Visualizar Centros Acadêmicos|Apresenta ao usuário a localização dos centros acadêmicos dentro do campus.|
|**UC10**|Visualizar Locais de Alimentação|Apresenta ao usuário a localização dos locais de alimentação dentro do campus.|
|**UC11**|Traçar rotas|Permite ao usuário, partindo da sua localização atual, traçar rotas para chegar a um destino desejado.|

### 6. Rastreabilidade

