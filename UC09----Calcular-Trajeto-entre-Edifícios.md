### 1. Descrição

Este caso de uso é destinado ao usuário da aplicação web. Através dele é possível calcular o trajeto entre edifícios do Campus Darcy Ribeiro da Universidade de Brasília.

### 2. Atores

* Usuário

### 3. Pré-condições

* Ter acessado a aplicação.
* Habilitar a localização atual.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

Este caso de uso se inicia quando o usuário determina pontos de partida e destino dentro do mapa.

* [FP01] - O usuário deverá habilitar as informações de sua localização.
* [FP02] - Após a verificação, a aplicação web irá localizar o usuário dentro do mapa.
* [FP03] - Uma tela irá aparecer para colocar o edifício de sua preferência.
* [FP04] - Após selecionar, o sistema irá apresentar uma rota até o local.
* [FP05] - O caso de uso é encerrado. 


#### 4.2 Fluxos Alternativos

* [FA01] - Cancelar o cálculo do trajeto.  
&nbsp;&nbsp;&bull; O usuário opta por calcular um trajeto.   
&nbsp;&nbsp;&bull; Acaba por cancelar sua ação antes do cálculo do trajeto.  
&nbsp;&nbsp;&bull; O caso de uso é encerrado.


#### 4.3 Fluxo de Exceção

* Não se aplica.

### 5. Regra de Negócio

* Não se aplica.

### 6. Pós-condição

* Após a consulta da localização, o usuário  poderá escolher o destino de sua preferência dentro do campus. 