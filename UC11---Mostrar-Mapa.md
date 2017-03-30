### 1. Descrição

O caso de uso é destinado ao usuário da aplicação web. Através dele é possível pesquisar no mapa da universidade por uma de instalação que esteja cadastrada na aplicação.

### 2. Atores

* Usuário

### 3. Pré-condições

* Ter acessado a aplicação.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

Este caso de uso é iniciado quando o usuário está na aplicação web e clicar na botão com ícone de lupa para pesquisar.

* [FP01] - O usuário escreve o nome do local desejado.
* [FP02] - O sistema mostra as informações do item pesquisado.
* [FP03] - O caso de uso é encerrado. 

#### 4.2 Fluxos Alternativos

* Não se aplica.

#### 4.3 Fluxo de Exceção

O fluxo de exceção inicia quando o local procurado pelo usuário não existe ou não está cadastrado no sistema.

* [FE01] - O sistema mostra uma mensagem informando que o edifício não existe e/ou não está cadastrado.
* [FE02] - O sistema redireciona o usuário para a tela inicial.
* [FE03] - O caso de uso é encerrado


### 5. Regra de Negócio

| Campo              | Formato                      | Obrigatoriedade | Valor       |
|--------------------|------------------------------|-----------------|-------------|
| Nome da instalação | String de até 150 caracteres | Sim             | Ex: BSA Sul |

### 6. Pós-condição

* Não se aplica.