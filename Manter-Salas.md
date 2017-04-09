### UC03 - Manter Salas

#### TC01 - Criar Sala com dados válidos
1. Descrição: O caso de teste verifica se os dados do registro estão válidos.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
3. Pós-Condições: Uma nova sala é cadastrada no banco de dados.
4. Dados Necessários: Turma, Tipo de Sala, Matérias, Nome do professor, Dias e horas de aula, Edifício, Nome, Local.

#### TC02 - Criar sala com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se algum dado de registro está preenchido de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para cadastro.
4. Dados Necessários: Turma, Tipo de Sala, Matérias, Nome do professor, Dias e horas de aula, Edifício, Nome, Local.

#### TC03 - Editar Sala com dados válidos
1. Descrição: O caso de teste verifica se os dados alterados estão válidos.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter todos os dados preenchidos corretamente.
3. Pós-Condições: As informações deverão ter sido editadas no banco de dados.  
4. Dados Necessários: Turma, Tipo de Sala, Matérias, Nome do professor, Dias e horas de aula, Edifício, Nome, Local.

#### TC04 - Editar sala com dados inválidos ou em branco
1. Descrição: O caso de teste verifica se os dados alterados estão preenchidos de forma incorreta ou em branco.
2. Pré-Condições: Estar autenticado como administrador na aplicação e ter algum dado preenchido de forma incorreta ou em branco.
3. Pós-Condições: O sistema apresenta mensagem de erro e retorna para o cadastro.
4. Dados Necessários: Turma, Tipo de Sala, Matérias, Nome do professor, Dias e horas de aula, Edifício, Nome, Local.

#### TC05 - Excluir Sala
1. Descrição: O caso de teste verifica se a sala foi excluído do mapa.
2. Pré-Condições: Estar autenticado como administrador na aplicação.
3. Pós-Condições: A sala deverá ter sido excluída do mapa.
4. Dados Necessários: Nenhum.
