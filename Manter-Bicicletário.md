### UC04 - Manter Bicicletário

#### TC01 - Criar Bicicletário com dados válidos
1. Descrição: O caso de teste verifica se os dados do registro estão válidos.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
3. Pós-Condições: Um novo bicicletário é cadastrado no banco de dados.
4. Dados Necessários: Nome e Local.

#### TC02 - Criar bicicletário com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se algum dado de registro está preenchido de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para cadastro.
4. Dados Necessários: Nome e Local.

#### TC03 - Editar Bicicletário com dados válidos
1. Descrição: O caso de teste verifica se os dados alterados estão válidos.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
3. Pós-Condições: As informações deverão ter sido editadas no banco de dados. 
4. Dados Necessários: Nome e Local.

#### TC04 - Editar bicicletário com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se os dados alterados estão preenchidos de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para o cadastro.
4. Dados Necessários: Nome e Local.

#### TC05 - Excluir Bicicletário
1. Descrição: O caso de teste verifica se o bicicletário foi excluído do mapa.
2. Pré-Condições: Estar autenticado como administrador na aplicação.
3. Pós-Condições: O bicicletário deverá ter sido excluído do mapa.
4. Dados Necessários: Nenhum.


