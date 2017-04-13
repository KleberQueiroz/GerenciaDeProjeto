### UC02 - Manter Departamentos
### 1. Descrição

Este caso de uso é destinado ao administrador e através deste é permitido criar, editar e excluir departamentos do mapa do campus.

### 2. Atores

* Administrador

### 3. Pré-condições

* O administrador deve estar devidamente autenticado no sistema.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal

* Este caso de uso se inicia quando o administrador seleciona Manter Departamentos.
1. O sistema exibe a tela de Manter Departamentos.
2. O administrador seleciona a opção desejada. **[FA01, FA02, FA03]**
3. O caso de uso é encerrado. 



#### 4.2 Fluxos Alternativos

**[FA01] - Criar**
* No passo 2 do fluxo principal, o administrador seleciona Criar.
1. O sistema apresenta um formulário de criação.
2. O administrador preenche as informações. [RN01]
3. O administrador confirma os dados.
4. O sistema salva as novas informações.

**[FA02] - Editar**
* No passo 2 do fluxo principal, o administrador seleciona Editar.
1. O sistema exibe uma tela com os departamentos cadastrados. 
2. É apresentada a tela para alteração dos dados do departamento.[RN01]
3. O administrador realiza as alterações. 
4. O administrador confirma os novos dados.
5. O sistema salva as novas informações.

**[FA03] - Excluir**
* No passo 2 do fluxo principal o administrador seleciona Excluir.
1. O sistema exibe uma tela com os departamentos cadastrados.
2. O administrador opta por excluir um departamento do mapa.

#### 4.3 Fluxo de Exceção

* Não se aplica.

### 5. Regra de Negócio

[RN01] - Dados de preenchimento

| Campo        | Formato                      | Obrigatoriedade | Valor                               |
|--------------|------------------------------|-----------------|-------------------------------------|
| Departamento | String de até 150 caracteres | Não             | Exemplo: Departamento de Matemática |
| Descrição    | String de até 150 caracteres | Sim             | -                                   |
| Sala         | String de até 150 caracteres | Sim             | Exemplo: Sala A                     |
| Nome         | String de até 150 caracteres | Sim             | Exemplo: Faculdade de Tecnologia    |
| Local        | Coordenadas locais           | Sim             | -                                   |

### 6. Pós-condição

* Não se aplica.