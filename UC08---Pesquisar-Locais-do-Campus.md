### UC08 - Pesquisar Locais do Campus
**1. Descrição:** 
* O caso de uso é destinado ao usuário da aplicação web. Através deste é possível pesquisar por um local no mapa da universidade.

**2. Atores:** 
* Usuário.

**3. Pré-Condições:** 
* Não se aplica.

### 4. Fluxo de Eventos 

**4.1 Fluxo Principal:** 
* Este caso de uso é iniciado quando o usuário clica no botão com ícone de lupa para pesquisar.
1. O usuário escreve o nome do local desejado. **[FE01] [RN01]**
2. O sistema mostra as informações do item pesquisado. **[UC08]**
3. O caso de uso é encerrado. 


**4.2. Fluxos Alternativos**
* Não se aplica.

**4.3. Fluxo de Exceção:** 
* [FE01] - Dados incorretos
1. O usuário insere o nome de um local que não existe ou não está cadastrado.
2. O sistema irá apresentar uma mensagem de erro.
3. O sistema retorna para o passo 1 do fluxo principal.

#### 5. Regra de Negócio: 

* [RN01] - Dados de preenchimento

| Campo            | Formato                      | Obrigatoriedade | Valor                            |
|------------------|------------------------------|-----------------|----------------------------------|
| Nome do local    | String de até 150 caracteres | Sim             | Exemplo: BSA Sul                 |

**6. Pós-condição:** 
* Não se aplica