### UC07 - Calcular Trajeto
**1. Descrição:** 
* Este caso de uso é destinado ao usuário, através deste é possível calcular o trajeto entre edifícios no mapa do campus.

**2. Atores:** 
* Usuário.

**3. Pré-Condições:** 
* Não se aplica.

### 4. Fluxo de Eventos 

**4.1 Fluxo Principal (FP):** 
* Este caso de uso se inicia quando o usuário determina pontos de partida e destino dentro do mapa.
1. O usuário clica em Calcular Trajeto. **[FA01]**
2. É apresentada uma tela para colocar os pontos de partida e destino. **[FE01] [RN01]**
3. O sistema irá apresentar uma rota até o local.
4. O caso de uso é encerrado. 

**4.2. Fluxos Alternativos**
* Não se aplica.

**4.3. Fluxo de Exceção:** 
* [FE01] - Dados incorretos
1. O usuário insere o nome de um local que não existe ou não está cadastrado.
2. O sistema irá apresentar uma mensagem de erro e o caso de uso se reinicia.


#### 5. Regra de Negócio: 

* [RN01] - Dados de preenchimento

| Campo            | Formato                      | Obrigatoriedade | Valor                            |
|------------------|------------------------------|-----------------|----------------------------------|
| Ponto de partida | String de até 150 caracteres | Sim             | Exemplo: Faculdade de Tecnologia |
| Ponto de destino | String de até 150 caracteres | Sim             | Exemplo: ICC Sul                 |

**6. Pós-condição:** 
* Não se aplica