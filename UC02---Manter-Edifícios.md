### 1. Descrição

Este caso de uso é destinado ao administrador que vai manter atualizado os dados da aplicação web. Através desse caso de uso é permitido criar, alterar e excluir os edifícios do Campus Darcy Ribeiro da Universidade de Brasília.

### 2. Atores

* Administrador

### 3. Pré-condições

* Ter acessado a aplicação.
* O usuário deve ter logado como administrador na aplicação.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

Este caso de uso se inicia quando o usuário administrador cria um edifício.

* [FP01] - O usuário administrador clica em criar um novo edifício.  
* [FP02] - Após clicar, o usuário é direcionado para a página de criação.  
* [FP03] - O usuário preenche as informações do edifício e clica em Salvar.
* [FP04] - O edifício é criado e pode ser visualizado. 
* [FP05] - Agora estará disponível o modo para editar e excluir edifício.
* [FP06] - O caso de uso é encerrado. 


#### 4.2 Fluxos Alternativos

* [FA01] - Cancelar a ação  
&nbsp;&nbsp;- O usuário administrador clica para cancelar a criação, edição ou exclusão do edifício.  
&nbsp;&nbsp;- Redirecionamento para a lista de edifícios.  
&nbsp;&nbsp;- O caso de uso é encerrado.  


#### 4.3 Fluxo de Exceção

* Não se aplica.

### 5. Regra de Negócio

* Não se aplica.

### 6. Pós-condição

* Após a criação do edifício será possível editar ou excluir o edifício.