### UC05 - Manter Pontos de Acesso

**1. Descrição:** Este caso de uso é destinado ao administrador e através deste é permitido criar, editar e excluir os pontos de acesso dos prédios do mapa do campus.

**2. Atores:** Administrador.

**3. Pré-Condições:** O administrador deve estar devidamente autenticado no sistema. 

#### 4. Fluxo de Eventos 

**4.1. Fluxo Principal:** Este caso de uso se inicia quando o administrador seleciona Manter Pontos de Acesso.
1. O sistema exibe a tela de Manter Pontos de Acesso.
2. O administrador seleciona a opção desejada. **[FA01, FA02, FA03]**
3. O caso de uso é encerrado. 

**4.2. Fluxos Alternativos**
**[FA01] - Criar**
1. No passo 2 do fluxo principal, o administrador seleciona Criar.
2. O sistema apresenta um formulário de criação.
3. O administrador preenche as informações.**[RN01]**
4. O administrador confirma os dados.
5. O sistema salva as novas informações.

**[FA02] - Editar**
1. No passo 2 do fluxo principal, o administrador seleciona Editar.
2. O sistema exibe uma tela com os pontos de acesso cadastrados. 
3. É apresentada a tela para alteração dos dados do ponto de acesso.**[RN01]**
4. O administrador realiza as alterações.
5. O administrador confirma os novos dados.
6. O sistema salva as novas informações.

**[FA03] - Excluir**
1. No passo 2 do fluxo principal, o administrador seleciona Excluir.
2. O sistema exibe uma tela com os pontos de acesso cadastrados.
3. O administrador opta por excluir um ponto de acesso do mapa.

**4.3. Fluxo de Exceção:** Não se aplica.
#### 5. Regra de Negócio: 
[RN01] - Dados de preenchimento

**6. Pós-condição:** Não se aplica.
