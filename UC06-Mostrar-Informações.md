### UC06 - Mostrar Informações 
**1. Descrição:** 
* Este caso de uso é destinado ao usuário da aplicação web. Através deste é possível visualizar as informações sobre os pontos cadastrados no mapa do campus. 

**2. Atores:** 
* Usuário.

**3. Pré-Condições:** 
* Não se aplica.

### 4. Fluxo de Eventos 

**4.1 Fluxo Principal (FP):** 
* Este caso de uso se inicia quando o usuário clica sobre um local cadastrado no mapa.
1. O usuário clica em um local cadastrado no mapa. **[FA01], [FA02], [FA03], [FA04], [FA05]**.
2. O sistema apresenta um painel lateral com informações.
3. O caso de uso é encerrado. 

**4.2. Fluxos Alternativos**

**[FA01]** - Este fluxo alternativo é iniciado quando o usuário clica em um edifício.
Retorna para **[FP02]**. 

**[FA02]** - Este fluxo alternativo é iniciado quando o usuário clica em um departamento.
Retorna para **[FP02]**. 

**[FA03]** - Este fluxo alternativo é iniciado quando o usuário clica em uma sala.
Retorna para **[FP02]**. 

**[FA04]** - Este fluxo alternativo é iniciado quando o usuário clica em um local de alimentação.
Retorna para **[FP02]**. 

**4.3. Fluxo de Exceção:** 

* Não se aplica.

#### 5. Regra de Negócio: 

* Não se aplica

**6. Pós-condição:** 
* Não se aplica