### 1. Descrição

Este caso de uso é destinado ao administrador que vai manter atualizado os dados da aplicação web. Através desse caso de uso é permitido criar, alterar e excluir os pontos de acesso dos edifícios do Campus Darcy Ribeiro da Universidade de Brasília.

### 2. Atores

* Administrador

### 3. Pré-condições

* Ter acessado a aplicação.
* O usuário deve ter logado como administrador na aplicação.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

Este caso de uso se inicia quando o administrador cria uma marcação para o ponto de acesso.

* [FP01] - O administrador clica em criar um novo ponto de acesso.  
* [FP02] - Após clicar, o administrador é direcionado para a página de criação.  
* [FP03] - O administrador preenche as informações do ponto de acesso e clica em Salvar.
* [FP04] - O ponto de acesso é criado e pode ser visualizado. 
* [FP05] - Agora estará disponível o modo para editar e excluir ponto de acesso.
* [FP06] - O caso de uso é encerrado. 


#### 4.2 Fluxos Alternativos

* [FA01] - Cancelar a ação  
&nbsp;&nbsp;&bull; O administrador clica para cancelar a criação, edição ou exclusão do ponto de acesso.  
&nbsp;&nbsp;&bull; Redirecionamento para a página do edifício.
&nbsp;&nbsp;&bull; O caso de uso é encerrado.  


#### 4.3 Fluxo de Exceção

* Não se aplica.

### 5. Regra de Negócio

* Não se aplica.

### 6. Pós-condição

* Após a criação do ponto de acesso será possível editá-lo ou excluí-lo.