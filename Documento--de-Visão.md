## Histórico de Revisões

| Data       | Versão | Descrição                                                                                                                                                                                                                         | Autor            |
|------------|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------|
| 16/03/2017 | 1.0    | Criação do documento.                                                                                                                                                                                                             | Lucas S.         |
| 17/03/2017 | 1.1    | Introdução.                                                                                                                                                                                                                       | Kairon Velozo    |
| 17/03/2017 | 1.2    | Escopo.                                                                                                                                                                                                                           | Mateus Roriz     |
| 19/03/2017 | 1.3    | Instrução do Problema; Definições, abreviações e acrônimos; Instrução de Posição do Produto; Principais Necessidades da Parte Interessada ou Usuário; Suposições e Dependências; Licenciamento e Instalação; Recursos do Produto. | Kairon Velozo    |
| 19/03/2017 | 1.4    | Propósito; Oportunidade de Negócios.                                                                                                                                                                                              | Jordan Miranda   |
| 19/03/2017 | 1.5    | Visão Geral do Produto e Perspectiva do Produto.                                                                                                                                                                                  | Mateus Roriz     |
| 19/03/2017 | 1.6    | Revisão da Instrução do Problema; Revisão da Instrução do Produto.                                                                                                                                                                | Taynara Carvalho |
| 19/03/2017 | 1.7    | Revisão da Introdução; Revisão do Escopo.                                                                                                                                                                                         | Sannya Arvelos   |
| 19/03/2017 | 1.8    | Resumo do Usuário; Ambiente do Usuário.                                                                                                                                                                                           | Lucas S.         |
| 20/03/2017 | 1.9    | Perfil do Usuário.                                                                                                                                                                                                                | Taynara Carvalho |
| 20/03/2017 | 2.0    | Oportunidade de Negócios; Referências.                                                                                                                                                                                              | Sannya Arvelos   |
| 20/03/2017 | 2.1    | Resumo dos Envolvidos; Perfis das Partes Interessadas; Resumo das Capacidades; Restrições; Faixas de Qualidades; Revisão de Principais Necessidades da Parte Interessada ou do Usuário.                                           | Lucas S.         |
| 21/03/2017 | 2.2    | Revisão das Oportunidades de Negócios; Instrução do Problema; Instrução de Posição do Produto; Resumo de Capacidade.                                                                                                              | Stéfane Souza    | S.  |

------

## Sumário

[1. Introdução](#1-introdução)  
&nbsp;&nbsp;[1.1. Propósito](#11-propósito)  
&nbsp;&nbsp;[1.2. Escopo](#12-escopo)  
&nbsp;&nbsp;[1.3. Definições, acrônimos e abreviações](#13-definições-acrônimos-e-abreviações)  
&nbsp;&nbsp;[1.4. Referências](#14-referências)  
[2. Posicionamento](#2-posicionamento)  
&nbsp;&nbsp;[2.1. Oportunidade de Negócios](#21-oportunidade-de-negócios)  
&nbsp;&nbsp;[2.2. Instrução do Problema ](#21-instrução-do-problema)  
&nbsp;&nbsp;[2.3. Instrução de Posição do Produto ](#23-instrução-de-posição-do-produto)  
[3. Envolvidos e Usuários](#03-envolvidos-e-usuários)  
&nbsp;&nbsp;[3.1. Resumo dos Envolvidos](#31-resumo-dos-envolvidos)  
&nbsp;&nbsp;[3.2. Resumo do Usuário](#32-resumo-do-usuário)  
&nbsp;&nbsp;[3.3. Ambiente do Usuário](#33-ambiente-do-usuário)  
&nbsp;&nbsp;[3.4. Perfis das Partes Interessadas](#34-perfis-das-partes-interessadas)  
&nbsp;&nbsp;&nbsp;&nbsp;[3.4.1. Equipe de Gestão de Projeto](#341-equipe-de-gestão-de-projeto)  
&nbsp;&nbsp;&nbsp;&nbsp;[3.4.2. Equipe de Desenvolvedores](#342-equipe-de-desenvolvedores)  
&nbsp;&nbsp;&nbsp;&nbsp;[3.4.3. Diretoria do CPD UnB](#343-diretoria-do-cpd-unb)  
&nbsp;&nbsp;[3.5. Perfis do Usuário](#35-perfis-do-usuário)  
&nbsp;&nbsp;[3.6. Principais Necessidades da Parte Interessada ou do Usuário](#36-principais-necessidades-da-parte-interessada-ou-do-usuário)  
[4. Visão Geral do Produto](#4-visão-geral-do-produto)  
&nbsp;&nbsp;[4.1. Perspectiva do Produto](#41-perspectiva-do-produto)  
&nbsp;&nbsp;[4.2. Resumo das Capacidades](#42-resumo-das-capacidades)  
&nbsp;&nbsp;[4.3. Suposições de Dependências](#43-suposições-e-dependências)  
[5. Recursos do Produto](#5-recursos-do-produto)  
[6. Restrições](#6-restrições)  
&nbsp;&nbsp;[6.1. Restrições Externas](#61-restrições-externas)  
&nbsp;&nbsp;[6.2. Restrições de Implementação](#61-restrições-de-implementação)  
[7. Faixas de Qualidade](#7-faixas-de-qualidade)  
&nbsp;&nbsp;[7.1. Requisitos do Sistema](#71-requisitos-do-sistema)  
&nbsp;&nbsp;[7.2. Requisitos de Desempenho](#72-requisitos-de-desempenho)  
&nbsp;&nbsp;[7.3. Requisitos Ambientais](#73-requisitos-ambientais)  

------

## 1. Introdução
Este documento tem o objetivo de apresentar uma visão completa sobre o software de mapeamento das instalações e de localização no Campus Darcy Ribeiro da Universidade de Brasília (UnB).

Espera-se que o leitor deste documento consiga compreender a finalidade global da aplicação UnBMapa. 

### 1.1. Propósito

O Software tem como propósito facilitar a locomoção entre as instalações do Campus Darcy Ribeiro da UnB, bem como a fácil localização de salas e outras dependências.

### 1.2. Escopo

O Centro de Processamento de Dados da Universidade de Brasília (CPD - UnB), é um órgão complementar da UnB que possui como intuito desenvolver as atividades de caráter permanente de apoio da pesquisa e da extensão ao desenvolvimento de ensino no que se refere ao processamento de dados, cujo os objetivos são promover e incentivar a informática na UnB, desenvolver, implantar e manter sistemas de mainframe e em microcomputadores e supervisionar, coordenar e controlar as atividades relacionadas com pesquisas referentes a hardware, software e rede de teleprocessamento.

O UnbMapa tem a finalidade de desenvolver o software de localização, via mapa, de algumas das instalações do Campus Darcy Ribeiro da UnB bem como de alguns de seus estabelecimentos.

### 1.3. Definições, acrônimos e abreviações

| Abreviação | Definição                                                     |
|------------|---------------------------------------------------------------|
| UnB        | Universidade de Brasília                                      |
| CPD - UnB  | Centro de Processamento de Dados da Universidade de Brasília. |

### 1.4. Referências 

UNIVERSIDADE DE BRASÍLIA. Institucional. Disponível em: <[http://www.unb.br/a-unb?menu=423](http://www.unb.br/a-unb?menu=423)>. Acesso em 20 março de 2017.

CENTRO DE PROCESSAMENTO DE DADOS DA UNIVERSIDADE DE BRASÍLIA. Sobre o CPD. Disponível em: <[http://www.cpd.unb.br/sobre-o-cpd](http://www.cpd.unb.br/sobre-o-cpd)>. Acesso em 20 março de 2017.

## 2. Posicionamento

### 2.1. Oportunidade de Negócios

O Campus Darcy Ribeiro é o mais antigo da Universidade de Brasília. Com o seu crescimento e criação de novos cursos, o número de pessoas que o circulam ficou cada vez maior e com isso a localização interna se tornou um problema. Segundo dados da universidade, mais de 50 mil pessoas frequentam diariamente o campus tendo mais de 500 mil m² de área construída. A plataforma web de mapeamento das instalações do campus Darcy Ribeiro veio com o propósito de auxiliar estudantes, servidores e visitantes da universidade facilitando a sua locomoção traçando trajetos pelos prédios.

### 2.2. Instrução do Problema 

| O problema seria      | A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro,      |
|-----------------------|---------------------------------------------------------------------------------------------------|
| afeta                 | estudantes, servidores e visitantes da universidade,                                              |
| cujo impacto é        | a demora para encontrar e chegar à determinado lugar na universidade,                             |
| uma boa solução seria | uma plataforma web que fornece as informações de localização de salas e prédios dentro do campus. |

### 2.3. Instrução de Posição do Produto  

| Para          | Estudantes, servidores e visitantes da universidade                                                                    |
|---------------|------------------------------------------------------------------------------------------------------------------------|
| Que           | desejam facilitar sua locomoção entre instalações do Campus Darcy Ribeiro                                              |
| O             | UnBMapa                                                                                                                |
| Que           | é uma plataforma web                                                                                                   |
| Diferente de  | Google Maps e mapas avulsos                                                                                            |
| Nosso produto | Possibilita a localização de edifícios, departamentos, salas e laboratórios do Campus Darcy Ribeiro pertencente a UnB. |

## 3. Envolvidos e Usuários

### 3.1. Resumo dos Envolvidos 

| Nome                        | Representa                                                                                                               | Função                                                                                                                                               |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Equipe de Desenvolvedores   | Grupo de discentes da Universidade de Brasília que estão matriculados na matéria Métodos de Desenvolvimento de Software. | Desenvolver e implementar a ferramenta web apresentada neste documento.                                                                              |
| Equipe de Gestão do Projeto | Grupo de discentes da UnB que estão matriculados na matéria Gestão de Portfólio de Projeto.                              | Desenvolver a aplicação web apresentada visando a detecção de possíveis riscos futuros, problemas e soluções viáveis para a conclusão deste projeto. |
| Clientes                    | Diretoria do CPD da UnB.                                                                                                 | Fornecer os dados necessários para o desenvolvimento e implementação da aplicação aqui apresentada.                                                  |

### 3.2. Resumo do Usuário  

| Nome         | Descrição                                                                                                                                                                 |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Novos alunos | Novos aprovados na UnB que nunca tiveram contato com o Campus Darcy Ribeiro.                                                                                              |
| Palestrantes | Pessoas de fora do Campus Darcy Ribeiro convidadas a ministrar algum tipo de palestra dentro do próprio e que não possuem conhecimento sobre suas localidades.            |
| Candidatos   | O Campus Darcy Ribeiro constantemente é local de provas de concursos, vestibulares e afins. Alguns destes também não possuem conhecimento sobre as localidades do campus. |
| Visitantes   | Pessoas que desejam conhecer as instalações do Campus Darcy Ribeiro e nunca estiveram em suas instalações.                                                                |

### 3.3. Ambiente do Usuário

O ambiente em que o usuário utilizará o sistema deverá ser um navegador com acesso à internet. Este navegador pode estar presente tanto em um computador desktop quanto um dispositivo móvel.

### 3.4. Perfis das Partes Interessadas

#### 3.4.1. Equipe de Gestão de Projeto

| Representantes        | Alexandre Torres Kryonidis, Daniel Moura da Silva, Eduardo Brasil Martins, Eduardo Quintino Gomes e Rafael dos Santos Rabetti.                                                                                                                     |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Gerentes do projeto.                                                                                                                                                                                                                                                   |
| Tipo                  | Grupo de discentes da Universidade de Brasília que estão matriculados na matéria Gestão de Portfólio de Projeto.                                                                                                                                   |
| Responsabilidades     | Gerir a equipe visando a entrega da ferramenta web aqui proposta de acordo com as metas e propostas entregues por eles.                                                                                                                            |
| Critérios de Sucesso  | Fazer com que o grupo de desenvolvedores possua um conhecimento uniforme, trabalhe bem em equipe. Seguir de forma correta um projeto de desenvolvimento de software visando a entrega, no prazo, de uma aplicação com um ótimo nível de qualidade. |
| Envolvimento          | Alto.                                                                                                                                                                                                                                              |
| Comentários/Problemas | Mesmo sendo uma equipe de alunos conseguir gerir uma equipe de outros alunos com objetivo de entregar um produto à um cliente real.                                                                                                                |

#### 3.4.2. Equipe de Desenvolvedores
| Representantes        | Jordan de Oliveira Miranda, Kairon Velozo, Lucas Soares Souza, Mateus Vieira da Silva Roriz, Sannya Santana de Arvelos, Stéfane Bogéa de Souza e Taynara de Jesus Carvalho. |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Desenvolvedores do projeto.                                                                                                                                                 |
| Tipo                  | Grupo de discentes da Universidade de Brasília que estão matriculados na matéria Métodos de Desenvolvimento de Software.                                                    |
| Responsabilidades     | Desenvolver, testar, implementar a aplicação neste documento apresentada.                                                                                                   |
| Critérios de Sucesso  | Fornecerem o software de acordo com o que foi estipulado pelo cliente e pela equipe da Gestão de Projeto.                                                                   |
| Envolvimento          | Alto.                                                                                                                                                                       |
| Comentários/Problemas | Trabalhar com ferramentas nunca, ou pouco, utilizadas pela a equipe para a implementação do projeto.                                                                        |


#### 3.4.3. Diretoria do CPD UnB

| Representante         | Felipe Santos.                                                                                               |
|-----------------------|--------------------------------------------------------------------------------------------------------------|
| Descrição             | Representante do CPD UnB                                                                                     |
| Tipo                  | Cliente do projeto.                                                                                          |
| Responsabilidades     | Fornecer os dados necessários para a conclusão da aplicação.                                                 |
| Critérios de Sucesso  | Receber um software que seja capaz de orientar as pessoas que precisem se localizar no Campus Darcy Ribeiro. |
| Envolvimento          | Alto.                                                                                                        |
| Comentários/Problemas | Conseguir fornecer um grande número de dados para a conclusão do projeto.                                    |

### 3.5 Perfis do Usuário

| Representantes        | Novos alunos, palestrantes, candidatos, visitantes.                                                                       |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Pessoas que vão ao Campus Darcy Ribeiro e nunca tiveram contato com o próprio.                                            |
| Tipo                  | Usuário Informal.                                                                                                         |
| Responsabilidades     | Acessar a aplicação e usá-la para localizar lugares.                                                                      |
| Critérios de Sucesso  | Encontrar o local desejado com facilidade.                                                                                |
| Envolvimento          | Baixo.                                                                                                                    |
| Comentários/Problemas | Pelo Campus Darcy Ribeiro ser muito extenso por muitas vezes se torna complicado se localizar dentro de suas instalações. |

### 3.6 Principais Necessidades da Parte Interessada ou do Usuário 

| Necessidade                          | Prioridade | Interesses                               | Solução Atual | Solução Proposta                                                     |
|--------------------------------------|------------|------------------------------------------|---------------|----------------------------------------------------------------------|
| Localização de Prédios               | Alta       | Se localizar entre os prédios do campus. | Google Maps   | Manter                                                               |
| Localização de Departamentos         | Alta       | Acesso aos departamentos                 | Google Maps   | Manter                                                               |
| Localização de Salas de Aula         | Alta       | Acesso às salas de aula                  | Não possui    | Mapeamento das áreas de maior circulação                             |
| Localização de Salas de Professores  | Alta       | Acesso às salas de professores           | Não possui    | Mapeamento das salas mais procuradas                                 |
| Localização de Laboratórios          | Alta       | Acesso aos laboratórios                  | Não possui    | Mapeamento dos laboratórios mais utilizados                          |
| Localização de locais de alimentação | Média      | Acesso aos locais de alimentação         | Google Maps   | Mapeamento de locais de alimentação como restaurantes e lanchonetes. |
| Localização de centros acadêmicos    | Baixa      | Acesso aos centros acadêmicos            | Não possui    | Mapeamento dos centros acadêmicos                                    |
| Trajetos entre edifícios             | Alta       | Transição entre edifícios.               | Google Maps   | Apresentação de rotas mais utilizadas                                |


## 4. Visão Geral do Produto

O sistema se propõe a oferecer uma forma alternativa para a localização entre o usuário e os prédios da UnB do Campus Darcy Ribeiro, além de fornecer uma maneira mais interativa para que os usuários possam mais intuitivamente achar os edifícios que procuram. Isto é feito utilizando-se uma interface baseada API do Google Maps, com ênfase nas mediações da UnB.  

### 4.1. Perspectiva do Produto

Além de oferecer uma forma mais intuitiva para localização dos edifícios, o sistema também disponibiliza apenas as rotas viáveis para locomoção com base em dados fornecidos pelos usuários conformes eles usam o sistema e conta com o display de estabelecimentos perto do usuário.

### 4.2 Resumo das Capacidades 

| Benefício para o Cliente                   | Recursos do Suporte                                                                                |
|--------------------------------------------|----------------------------------------------------------------------------------------------------|
| Informar a localização do usuário          | Permite o usuário saber de sua localização atual onde esteja dentro do campus.                     |
| Traçar rotas de locomoção dentro do campus | Permite que o usuário tenha uma rota para chegar até o seu destino.                                |
| Pesquisa por departamento, sala, edifício  | Área de acesso à informações sobre os locais.                                                      |
| Calcular trajeto                           | Permite que o usuário tenha uma estimativa de tempo até o destino desejado                         |
| Mostrar informações do edifício            | Área para o acesso à informações do edifício.                                                      |
| Disponibilizar matérias por edifício       | Usuários poderão visualizar as matérias ministradas nas salas de acordo com dia, hora e professor. |

### 4.3. Suposições e Dependências

| Suposição                                                   | Recurso Afetado                                                                                            |
|-------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| O usuário terá conexão de internet durante o uso do sistema | Toda a aplicação é afetada pois o usuário necessidade de conexão com de internet durante o uso do serviço. |

## 5. Recursos do Produto

| Recurso                                   | Descrição                                                                                                                                         |
|-------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| Interface Responsiva                      | A interface do usuário é adaptável aos diversos tamanhos e resoluções de tela, podendo ser utilizado em Desktops, Laptops, Tablets e Smartphones. |
| Pesquisa de Departamentos                 | Possibilita o usuário encontrar a localização de um departamento através do nome ou sigla.                                                        |
| Trajeto entre edifícios                   | Permite que o usuário consulte o trajeto entre edifícios do campus.                                                                               |
| Pesquisa de Salas de Aulas e Laboratórios | Permite que o usuário localizar salas e/ou laboratórios onde uma determinada aula é ministrada de acordo com a disciplina e turma.                |
| Pesquisa de Sala de Professores           | Permite que o usuário localize a sala de um professor através do seu nome.                                                                        |
| Painel Administrativo                     | Possibilita o cliente, alterar e incluir informações que serão disponibilizadas publicamente.                                                     |
## 6. Restrições

### 6.1. Restrições Externas

Os usuários deverão possuir acesso a internet para usufruir do UnBMapa, isso acontece porque as informações são exibidas ao usuário por demanda, não havendo, portanto, o armazenamento local dos dados exibidas, de modo que permitisse o funcionamento offline do UnBMapa.

O Campus Darcy Ribeiro possui vários eventos que, por vezes, modificam o seu funcionamento. Dessa forma, as informações fornecidas através do UnBMapa podem ficar temporariamente desatualizadas.

### 6.2. Restrições de Implementação

A experiência da equipe com o uso das tecnologias utilizadas para a implementação do UnBMapa e o tamanho da equipe são restrições. Tais restrições podem reduzir o escopo do projeto para que o mesmo seja entregue.


## 7. Faixas de Qualidade

### 7.1. Requisitos do Sistema

O serviço deverá funcionar ao menos nos seguintes navegadores: Firefox, Chrome, Chromium, Edge, Safari, Opera e Internet Explorer.

### 7.2. Requisitos de Desempenho

A aplicação deve responder de forma mais otimizada possível já que terá foco sobre a localização atual do usuário e seu caminho até uma outra localidade.

### 7.3. Requisitos Ambientais

A aplicação será dependente de conexão à internet pois todos os seus dados serão processados no servidor para somente após serem passados aos usuários.