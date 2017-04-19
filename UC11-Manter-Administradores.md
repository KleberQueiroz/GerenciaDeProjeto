### 1. Descrição

O caso de uso é destinado ao administrador. Através dele é possível gerenciar as contas de administradores na aplicação.

### 2. Atores

* Adminstrador.

### 3. Pré-condições

* O administrador deve estar logado na aplicação.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal
Este caso de uso de inicia quando o administrador seleciona a opção de Manter Administradores.
 
1. O sistema exibe a página de Manter Administradores. 
2. O administrador seleciona a opção desejada. **[FA01, FA02, FA03]** 
3. O caso de uso é encerrado.

#### 4.2 Fluxos Alternativos

**[FA01] - Criar**

1. No passo 2 do fluxo principal o administrador seleciona Criar.
2. O sistema apresenta um formulário de criação. **[RN01]**
3. O administrador preenche as informações. **[FE01],[FE02]**
4. O administrador confirma os dados.
5. O sistema salva as novas informações no banco de dados.
6. O sistema retorna para o passo 3 do fluxo principal.


**[FA02] - Editar**

1.No passo 2 do fluxo principal, o sistema exibe a lista de administradores cadastros e seleciona Editar.
2. É apresentada a tela para alteração de dados do administrador. **[RN01],[FE01],[FE02]**  
3. O administrador realiza as alterações.  
4. O administrador confirma os novos dados.  
5. O sistema salva as informações no banco de dados.
6. O sistema retorna para o passo 3 do fluxo principal.

**[FA03] - Excluir**

1. No passo 2 do fluxo principal, o sistema exibe a lista de administradores cadastrados e seleciona Excluir.  
2. O administrador confirma por excluir um administrador do sistema. 
3. O sistema retorna para o passo 3 do fluxo principal. 

#### 4.3 Fluxo de Exceção

**[FE01]** - Email já cadastrado ou inválido
1. O administrador informa um e-mail já cadastrado.  
2. O sistema irá apresentar uma mensagem de erro.
3. O sistema retorna para o passo 2 do fluxo principal.


**[FE02]** - Senha sem tamanho mínimo
1. O adminstrador informa uma senha sem o mínimo de caracteres requeridos.   
2. O sistema irá apresentar uma mensagem de erro.
3. O sistema retorna para o passo 2 do fluxo principal.


### 5. Regra de Negócio

[RN01] - Dados de preenchimento.

| Campo | Formato                          | Obrigatoriedade | Valor                      |
|-------|----------------------------------|-----------------|----------------------------|
| Nome  | String de até 255 caracteres     | Sim             | Exemplo: José              |
| Email | String de até 255 caracteres     | Sim             | Exemplo: exemplo@email.com |
| Senha | String de no mínimo 6 caracteres | Sim             | Exemplo: 56labce           |

### 6. Pós-condição

* Não se aplica.