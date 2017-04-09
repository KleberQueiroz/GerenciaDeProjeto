### UC01 - Manter Edifícios

#### TC01 - Criar Edifício com dados válidos
1. Descrição: O caso de teste verifica se os dados do registro estão válidos. 
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
3. Pós-Condições: Um novo edifício é cadastrado no banco de dados.
4. Dados Necessários: Departamento, Descrição, Sala, Nome e Local.

#### TC02 - Criar edifício com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se algum dado de registro está preenchido de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para o cadastro.
4. Dados Necessários: Departamento, Descrição, Sala, Nome e Local.

#### TC03 - Editar Edifício com dados válidos
1. Descrição: O caso de teste verifica se os dados alterados estão válidos.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
3. Pós-Condições: As informações deverão ter sido editadas no banco de dados. 
4. Dados Necessários: Departamento, Descrição, Sala, Nome e Local.

#### TC04 - Editar edifício com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se os dados alterados estão preenchidos de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para o cadastro.
4. Dados Necessários: Departamento, Descrição, Sala, Nome e Local.

#### TC05 - Excluir Edifício
1. Descrição: O caso de teste verifica se o edifício foi excluído do mapa.
2. Pré-Condições: Estar autenticado como administrador na aplicação.
3. Pós-Condições: O edifício deverá ter sido excluído do mapa.
4. Dados Necessários: Nenhum.
