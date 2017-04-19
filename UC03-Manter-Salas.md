### UC03 - Manter Salas

### 1. Descrição

Este caso de uso é destinado ao administrador e através deste é permitido criar, editar e excluir salas do mapa do campus.

### 2. Atores

* Administrador

### 3. Pré-condições

* O administrador deve estar devidamente autenticado no sistema. 

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

* Este caso de uso se inicia quando o administrador seleciona Manter Salas.

1. O sistema exibe a tela de Manter Salas.
2. O administrador seleciona a opção desejada. **[FA01, FA02, FA03]**
3. O caso de uso é encerrado. 

#### 4.2 Fluxos Alternativos

**[FA01] - Criar**
1. No passo 2 do fluxo principal, o administrador seleciona Criar.
2. O sistema apresenta um formulário de criação. **[RN01]**
3. O administrador preenche as informações. **[FE01]**
4. O administrador confirma os dados.
5. O sistema salva as novas informações.
6. O sistema retorna para o passo 3 do fluxo principal.

**[FA02] - Editar**
1. No passo 2 do fluxo principal, o administrador seleciona Editar.
2. O sistema exibe uma tela com as salas cadastrados. 
3. É apresentada a tela para alteração dos dados da salas. **[RN01]**
4. O administrador realiza as alterações. **[FE01]**
5. O administrador confirma os novos dados.
6. O sistema salva as novas informações.
7. O sistema retorna para o passo 3 do fluxo principal.

**[FA03] - Excluir**
1. No passo 2 do fluxo principal, o administrador seleciona Excluir.
2. O sistema exibe uma tela com as salas cadastrados.
3. O administrador opta por excluir uma sala do mapa.
4. O sistema retorna para o passo 3 do fluxo principal.


#### 4.3 Fluxo de Exceção

**[FE01] - Dados Inválidos**
1. No passo 2 do fluxo principal, selecionando a opção **[FA01]** ou **[FA02]** se o sistema identificar algum dado inválido é exibida uma mensagem de erro e retorna para a página de cadastro ou edição. 
2. O sistema retorna para o passo 2 do fluxo principal.

### 5. Regra de Negócio

[RN01] - Dados de preenchimento

| Campo               | Formato                      | Obrigatoriedade | Valor                               |
|---------------------|------------------------------|-----------------|-------------------------------------|
| Turma               | String de até 10 caracteres  | Sim             |Exemplo: Turma A                     |
| Tipo de Sala        | String de até 150 caracteres | Sim             | Exemplo: Secretária, Centro Acadêmico, Sala de Aula|
| Matérias            | String de até 100 caracteres | Sim             | Exemplo: Cálculo 1                  |
| Nome do professor   | String de até 100 caracteres | Não             |  -                                  |
| Dias e horas de aula| String de até 100 caracteres | Não             | Exemplo: Terça de 14h até 16h       |                        
| Nome                | String de até 150 caracteres | Sim             | Exemplo: Sala B - Subsolo           |
| Local               | Coordenadas locais           | Sim             | -                                   |
| Edifício            | String de até 150 caracteres | Sim             | Exemplo:  Faculdade de Arquitetura  |

### 6. Pós-condição

* Não se aplica.