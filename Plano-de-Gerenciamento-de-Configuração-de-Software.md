### Histórico de Revisões

| Data | Versão | Descrição | Autor |
|:----:|:------:|:---------:|:-----:|
|19/03/2017| 1.0 | Criação da estrutura do documento | Eduardo Brasil |
|19/03/2017| 1.1 | Introdução, Objetivo e Ferramentas | Eduardo Brasil |
|19/03/2017| 1.2 | Git/Github | Eduardo Brasil |
|20/03/2017| 1.3 | Circle CI | Matheus Mello |
|04/04/2017| 1.4 | Repositório do projeto, Politica de branch, Commits e Politica de aprovação| Eduardo Brasil |
|07/04/2017| 1.0 | Deploy | Rafael Rabetti |

***

## Sumário
1.   [Introdução](#1-introdução)

2.   [Objetivo](#2-objetivo)

3.   [Ferramentas](#3-Ferramentas)

4.   [Git/Github](#4-Git/Github)

5.   [Deployment](#5-Deployment)



### 1. Introdução

Este Plano de Gerenciamento de Configuração tem como objetivo auxiliar o projeto Localização Darcy. Tal plano visa controlar as mudanças que ocorrerão durante o ciclo de vida do projeto e Almeja guiar os envolvidos no projeto para as boas práticas, manter a integridade do desenvolvimento e do projeto assim como facilitar o controle de mudanças.

### 2. Objetivo

Este Plano de Gerenciamento de Configuração tem como finalidade ser a base para as decisões tomadas no projeto no que se diz respeito à gerência de configuração de software.

##### Definições,Acrônimos e Abreviações 

| Sigla | Descrição |
|:----:|:------:|
|CM|	Gerência de Configuração (Management Configuration)|
|CI|	Integração Contínua (Continuous Integration)|

Atividades a Serem desenvolvidas neste plano.

 * Estabelecer politicas de CM
 * Escrever Plano de CM

### 3. Ferramentas   

| Ferramenta | Descrição |
|:----:|:------:|
|Git|	Controle de versão de código|
|Github| que sera utilizado como repositório oficial do Software|
|Sublime text| 	Editor de Texto|
|Circle CI|	Ferramenta de integração continua|


#### 3.2 _Git_/_GitHub_  

O git é uma ferramenta de controle de versão distribuído, possuindo forte suporte para desenvolvimento não-linear.
O Github é um Forge para a ferramenta de controle de versão git, e também pode ser utilizada como ferramenta de gerenciamento de projetos.

##### 3.2.1 Repositórios do projeto

O repositório do projeto se encontra no link [Onde é UnB](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB)

##### 3.2.2 Política de _branches_

O repositório possuira duas branches principais: Master e a devel. A branch master deverá conter a última versão estável do projeto e a branch devel será utilizada para integração das funcionalidades desenvolvidas e teste antes de ser incorporada à master.
No repositório de desenvolvimento, as branches serão criadas e nomeadas de acordo com os casos de uso.

O nome da branch, deverá seguir o seguinte padrão:
UC< número do caso de uso conforme foram priorizados > e a descrição breve do mesmo, composta pelo nome do caso de uso iniciado com letra maiúscula e em inglês >.
Exemplo : "UC01-MaintainUser".

##### 3.2.4 Commits

Os desenvolvedores irão commitar logo após construirem um componente da funcionalidade com o nome da branch que esteja funcionando de forma completa, ou seja já testada
As mensagens dos commits deverão seguinte este padrão: < Descrição do escopo do commit na em inglês sempre iniciado de letra maiúscula e com um verbo no gerúndio >. Exemplo: "Registering user".

##### 3.2.5 Política de aprovação do código

Após todas as funcionalidades terem sido desenvolvidas nas branches e finalizadas elas deverão ser integradas à branch devel, após a funcionalidade ser integrada a dével deverá ser realizado um pull request para o repositório remoto. O label do pull request deve ser ser nomeado igual o nome do caso de uso desenvolvido.
A equipe será responsável por revisar os pull request e fazer a integração com a branch devel do repositório remoto, quando as funcionalidades da iteração forem todas concluidas e testadas, elas deverão ser integradas a branch master do repositório oficial.


#### 3.3 _Circle CI_  

Circle CI é uma ferramenta de integração contínua e deploy para projetos hospedados no GitHub. Nele é possível criar uma build em cada commit, passando por todos os testes unitários e de integração. Garantindo assim que a versão no servidor será sempre a última versão estável do software.

### 4. _Deployment_  

Ao longo do desenvolvimento a aplicação ficará hospedada no heroku. Depois de concluído o projeto o sistema deverá ser hospedado em algum servidor da UnB