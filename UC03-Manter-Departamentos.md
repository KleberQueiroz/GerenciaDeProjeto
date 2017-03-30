### 1. Descrição

Este caso de uso é destinado ao administrador que vai manter atualizado os dados da aplicação web. Através desse caso de uso é permitido criar, alterar e excluir os departamentos do Campus Darcy Ribeiro da Universidade de Brasília.

### 2. Atores

* Administrador

### 3. Pré-condições

* Ter acessado a aplicação.
* O usuário deve ter logado como administrador na aplicação.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

Este caso de uso se inicia quando o usuário administrador cria um departamento.

* [FP01] - O administrador clica em criar um novo departamento.  
* [FP02] - Após clicar, o usuário é direcionado para a página de criação.  
* [FP03] - O administrador preenche as informações do departamento e clica em Salvar.
* [FP04] - O departamento é criado e pode ser visualizado. 
* [FP05] - Agora estará disponível o modo para editar e excluir o departamento.
* [FP06] - O caso de uso é encerrado. 


#### 4.2 Fluxos Alternativos

* [FA01] - Cancelar a ação  
&nbsp;&nbsp;- O administrador clica para cancelar a criação, edição ou exclusão do departamento.  
&nbsp;&nbsp;- Redirecionamento para a lista de departamentos.  
&nbsp;&nbsp;- O caso de uso é encerrado.  


#### 4.3 Fluxo de Exceção

* Não se aplica.

### 5. Regra de Negócio

* Não se aplica.

### 6. Pós-condição

* AApós a criação do departamento será possível editar ou excluir o departamento.