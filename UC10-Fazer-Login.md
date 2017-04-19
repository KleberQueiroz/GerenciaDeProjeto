### 1. Descrição

O caso de uso é destinado ao administrador para efetuar o login na aplicação.

### 2. Atores

* Adminstrador.

### 3. Pré-condições

* Ter um registro como administrador no site. 

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal
Este caso de uso é iniciado quando o administrador deseja autenticar-se na aplicação.  
 
1. O administrador acessa a página de login.  
2. Informa o e-mail e a senha e clica no botão de logar.  
3. O administrador é autenticado na aplicação.  
4. O caso de uso é encerrado.  

#### 4.2 Fluxos Alternativos

* Não se aplica.  

#### 4.3 Fluxo de Exceção

**[FE01]** - Dados incorretos  
1. O administrador informa os dados de acesso incorretos.  
2. O sistema irá apresentar uma mensagem de erro.
3. O sistema retorna para o passo 1 do fluxo principal.  


### 5. Regra de Negócio

[RN01] - Dados de preenchimento.

| Campo | Formato                          | Obrigatoriedade | Valor                      |
|-------|----------------------------------|-----------------|----------------------------|
| Email | String de até 255 caracteres    | Sim             | Exemplo: exemplo@email.com |
| Senha | String de no mínimo 6 caracteres | Sim             | Exemplo: 56labce           |

### 6. Pós-condição

* Não se aplica.