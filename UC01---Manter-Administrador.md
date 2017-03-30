### 1. Descrição

Este caso de uso é destinado ao usuário administrador através deste é possível acessar a área restrita da aplicação web o que permite que este crie, edite ou exclua algo no site.

### 2. Atores

* Administrador

### 3. Pré-condições

* Ter acessado a aplicação.
* O administrador deve possuir registro na aplicação.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

Este caso de uso é iniciado quando o usuário realiza o login como administrador na aplicação.

* [FP01] - O usuário acessa a aplicação.
* [FP02] - Realiza login como administrador e é redirecionado para o painel administrativo.
* [FP03] - Após a autenticação do seu registro, será possível criar, editar ou excluir qualquer tipo de dado do mapa do campus da universidade.
* [FP04] - O usuário atualiza as informações e realiza a saída da conta como administrador.
* [FP05] - O caso de uso é encerrado.

#### 4.2 Fluxos Alternativos

* Não se aplica.

#### 4.3 Fluxo de Exceção

* [FE01] - Dados inválidos: No momento do login, se a entrada de algum dado incorreto for detectado pelo sistema, será exibida uma mensagem notificando o erro.

### 5. Regra de Negócio

| Campo    | Formato                           | Obrigatoriedade | Valor                    |
|----------|-----------------------------------|-----------------|--------------------------|
| email    | String de até 255 caracteres      | Sim             | Exemplo: email@email.com |
| password | String com no mínimo 6 caracteres | Sim             |                          |

### 6. Pós-condição

* Não se aplica.