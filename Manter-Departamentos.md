### UC02 - Manter Departamentos

#### TC01 - Criar Departamento
1. Descrição: O caso de teste verifica se os dados do registro estão válidos.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
3. Pós-Condições: Um novo departamento é cadastrado no banco de dados.
4. Dados Necessários: Edifícios, Descrição, Sala, Nome, Local.

#### TC02 - Criar departamento com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se algum dado de registro está preenchido de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para cadastro.
4. Dados Necessários: Edifícios, Descrição, Sala, Nome, Local.

#### TC03 - Editar Departamento com dados válidos
1. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
2. Pós-Condições: As informações deverão ter sido editadas no banco de dados.  
3. Dados Necessários: Edifícios, Descrição, Sala, Nome, Local.

#### TC04 - Editar departamento com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se os dados alterados estão preenchidos de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para o cadastro.
4. Dados Necessários: Edifícios, Descrição, Sala, Nome, Local.

#### TC05 - Excluir Departamento 
1. Descrição: O caso de teste verifica se o departamento foi excluído do mapa.
2. Pré-Condições: Estar autenticado como administrador na aplicação.
3. Pós-Condições: O departamento deverá ter sido excluído do mapa.
4. Dados Necessários: Nenhum.
