### 1. Descrição

Este caso de uso é destinado a mostrar ao usuário o mapa do campus.

### 2. Atores

* Usuário

### 3. Pré-condições

* Não se aplica.

### 4. Fluxo de Eventos

#### 4.1 Fluxo Principal
* Este caso de uso é iniciado quando o usuário abre a aplicação web.
1. O mapa do campus é exibido para o usuário. **[FA01] [RN01]**
2. O caso de uso é encerrado. 

#### 4.2 Fluxos Alternativos

**[FA01]** - O caso de uso se inicia quando o usuário amplia a imagem do mapa.
1. O usuário verá as especificações do mapa de acordo com o zoom.

#### 4.3 Fluxo de Exceção

* Não se aplica.

### 5. Regra de Negócio

[RN01] - Locais que serão apresentados do mapa de acordo com a interação do usuário com a aplicação.

| Local                 | Descrição                                                                               | Valor                          |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------------|
| Edifícios             | Locais que abrigam atividades da universidade.                                          | Ex: Reitoria, Biblioteca.      |
| Departamentos         | Espaços onde se localizam atividades relacionadas a determinadas áreas de conhecimento. | Ex:Departamento de Matemática. |
| Centro Acadêmicos     | Entidade que representa todos os estudantes de um curso.                                | Ex: CA de Engenharia.          |
| Salas                 | Locais onde são ministradas aulas ou sala de professores.                               | Ex: BT-23/1                    |
| Locais de Alimentação | Locais onde pode-se comprar comida.                                                     | Ex: RU.                        |
| Bicicletários         | Locais destinados para estacionamento de bicicletas.                                    | Não se aplica.                 |
| Pontos de Acesso      | Pontos de entrada e saída de determinado local.                                         | Não se aplica.                 |

### 6. Pós-condição

* Não se aplica.