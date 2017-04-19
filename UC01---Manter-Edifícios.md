### UC01 - Manter Edifícios

### 1. Descrição

1. Descrição: Este caso de uso é destinado ao administrador e através deste é permitido criar, editar e excluir edifícios do mapa do campus.

### 2. Atores

* Administrador

### 3. Pré-condições

* O administrador deve estar devidamente autenticado no sistema. 

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

* Este caso de uso se inicia quando o administrador seleciona Manter Edifício.
1. O sistema exibe a tela de Manter Edifício.
2. O administrador seleciona a opção desejada. **[FA01, FA02, FA03]**
3. O caso de uso é encerrado. 

#### 4.2 Fluxos Alternativos

**[FA01] - Criar**
1. No passo 2 do fluxo principal, o administrador seleciona Criar.
2. O sistema apresenta um formulário de criação. **[RN01]**
3. O administrador preenche as informações. **[FE01]**
4. O administrador confirma os dados.
5. O sistema salva as novas informações no banco de dados.
6. O sistema vai para para o passo 3 do fluxo principal.

**[FA02] - Editar**
1. No passo 2 do fluxo principal, o administrador seleciona Editar.
2. O sistema exibe uma tela com os edifício cadastrados. 
3. É apresentada a tela para alteração dos dados do edifício. **[RN01]**
4. O administrador realiza as alterações. **[FE01]**
5. O administrador confirma os novos dados.
6. O sistema salva as novas informações no banco de dados.
7. O sistema vai para para o passo 3 do fluxo principal. 

**[FA03] - Excluir**
1. No passo 2 do fluxo principal, o administrador seleciona Excluir.
2. O sistema exibe uma tela com os edifícios cadastrados.
3. O administrador opta por excluir um edifício do mapa.
4. O sistema vai para para o passo 3 do fluxo principal. 

#### 4.3 Fluxo de Exceção

**[FE01] - Dados Inválidos**
1. No passo 2 do fluxo principal, selecionando a opção **[FA01]** ou **[FA02]** se o sistema identificar algum dado inválido é exibida uma mensagem de erro e retorna para a página de cadastro ou edição. 
2. O sistema retorna para o passo 2 do fluxo principal.

### 5. Regra de Negócio

[RN01] - Dados de preenchimento

| Campo               | Formato                     | Obrigatoriedade | Valor               |
|---------------------|-----------------------------|-----------------|---------------------|
| Acrônimo            | String de até 20 caracteres | Sim             | Exemplo: ICC        |
| Nome                | String de até 50 caracteres | Sim             | -                   |
| Telefone            | String de até 11 caracteres | Sim             | Exemplo: 12345678   |
| Latitude e Longitude| Coordenadas locais          | Sim             | -                   |



### 6. Pós-condição

* Não se aplica.