## Histórico de Revisões

|      Data     | Versão | Descrição                                                                | Autor         |
|---------------|--------|--------------------------------------------------------------------------|---------------|
|  16/03/2017   |  0.1  | Criação do documento                                                     | Lucas S.      |
|  17/03/2017   |  0.2   | Introdução e Escopo                | Kairon Velozo, Mateus Roriz|
|  19/03/2017   |  0.3   | Introdução do Problema; Definições, Abreviações e acrônimos; Instrução de Posição do Produto; Principais Necessidades da Parte Interessada; Suposições e Dependências; Licenciamento e Instalação; Recursos do Produto; Propósito; Oportunidade de Ńegócio; Visão Geral do Produto e Perspectiva do Produto  | Karion Velozo, Jordan Miranda, Mateus Roriz |
|  19/03/2017   |  0.4   | Instrução do produto (Criação de tabelas); Melhoria na Introdução e no escopo; Resumo do Usuário e Ambiente do Usuário | Taynara Carvalho, Sannya Arvelos, Lucas S. |
| 20/03/2017    |  0.5   | Perfil do Usuário; Oportunidade de Negócio/Referências; Resumo dos Envolvidos; Perfis das Partes Interessadas; Resumo das Capacidades; Restrições; Faixas de Qualidade; Completando a tabela de Principais Necessidades da Parte Interessada | Taynara Carvalho, Sannya Arvelos, Lucas S. |
| 21/03/2017    |  0.6   | Alterações em Oportunidades de Negócios, Instrução do Problema; Instrução de Posição do Produto; Resumo de Capacidade | Stéfane Souza |
| 23/03/2017    |  0.7   | Perfis de Usuário: Novos Alunos, Palestrantes | Lucas S., Sannya Arvelos |
| 06/04/2017    |  0.8   | Refatoração do documento, adição de requisitos funcionais e não funcionais, legendas das prioridades. | Taynara, Sannya Arvelos, Lucas S., Kairon Velozo|
| 07/04/2017    |  0.9   | Migração de documento do Google Drive para a Wiki. Pequenas alterações feitas em texto. | Lucas S. |
| 13/04/2017    |  0.9.1   | Refatoração de seções do documento. | Lucas S., Kairon Velozo |
------

## Sumário

[1. Introdução](#1-introdução)  
&nbsp;&nbsp;[1.1. Propósito](#11-propósito)  
&nbsp;&nbsp;[1.2. Definições, acrônimos e abreviações](#12-definições-acrônimos-e-abreviações)  
&nbsp;&nbsp;[1.3. Referências](#13-referências)  
[2. Posicionamento](#2-posicionamento)  
&nbsp;&nbsp;[2.1. Oportunidade de Negócios](#21-oportunidade-de-negócios)  
&nbsp;&nbsp;[2.2. Instrução do Problema ](#21-instrução-do-problema)  
&nbsp;&nbsp;[2.3. Instrução de Posição do Produto ](#23-instrução-de-posição-do-produto)  
[3. Envolvidos e Usuários](#3-envolvidos-e-usu%C3%A1rios)  
&nbsp;&nbsp;[3.1. Resumo dos Envolvidos](#31-resumo-dos-envolvidos)  
&nbsp;&nbsp;[3.2. Resumo do Usuário](#32-resumo-do-usu%C3%A1rio)  
&nbsp;&nbsp;[3.3. Perfis das Partes Interessadas](#33-perfis-das-partes-interessadas)    
&nbsp;&nbsp;&nbsp;[3.3.1 Equipe de Gestão de Projeto](#331-equipe-de-gest%C3%A3o-de-projeto)    
&nbsp;&nbsp;&nbsp;[3.3.2 Equipe de Desenvolvedores](#331-equipe-de-desenvolvedores)    
&nbsp;&nbsp;&nbsp;[3.3.2 Diretoria do CPD UnB](#333-diretoria-do-cpd-unb)   
&nbsp;&nbsp;[3.4. Perfil dos Usuários](#34-perfil-dos-usuários)  
&nbsp;&nbsp;&nbsp;[3.4.1 Novos Alunos](#341-novos-alunos)   
&nbsp;&nbsp;&nbsp;[3.4.2 Palestrantes](#342-palestrantes)   
&nbsp;&nbsp;&nbsp;[3.4.3 Visitantes](#343-visitantes)   
&nbsp;&nbsp;&nbsp;[3.4.2 Candidatos](#344-candidatos)     
&nbsp;&nbsp;[3.5. Principais Necessidades da Parte Interessada ou do Usuário](#35-principais-necessidades-da-parte-interessada-ou-do-usuário)  
[4. Visão Geral do Produto](#4-visão-geral-do-produto)  
&nbsp;&nbsp;[4.1. Perspectiva](#41-perspectiva)  
&nbsp;&nbsp;[4.2. Benefícios](#42-benefícios)  
&nbsp;&nbsp;[4.3. Licenciamento](#43-licenciamento)  
[5. Requisitos](#5-requisitos)  
&nbsp;&nbsp;[5.1 Requisitos Funcionais](#51-requisitos-funcionais)      
&nbsp;&nbsp;[5.2 Requisitos Não Funcionais](#52-requisitos-não-funcionais)     

------

## 1. Introdução
<p align ="justify">A finalidade deste documento é coletar, analisar e definir as necessidades e recursos de nível superior do sistema de mapeamento das instalações e de localização do Campus Darcy Ribeiro da Universidade de Brasília (UnB). O documento se concentra nos recursos necessários aos envolvidos, usuários e nas razões que levam as necessidades, e também estabelece uma visão geral e clara do projeto para todos os envolvidos.  
<p align ="justify">Espera-se que o leitor deste documento consiga compreender a finalidade global da aplicação "Onde É? UnB"   

### 1.1. Propósito  

<p align ="justify">O "Onde É? UnB" tem a finalidade de facilitar a localização, via mapa interativo, de algumas das instalações e estabelecimentos do Campus Darcy Ribeiro da UnB.  
  
### 1.2. Definições, acrônimos e abreviações  

| Abreviação | Definição                                                     |
|------------|---------------------------------------------------------------|
| UnB        | Universidade de Brasília                                      |
| CPD - UnB  | Centro de Processamento de Dados da Universidade de Brasília. |

### 1.3. Referências   

UNIVERSIDADE DE BRASÍLIA. Institucional. Disponível em: <[http://www.unb.br/a-unb?menu=423](http://www.unb.br/a-unb?menu=423)>. Acesso em 20 março de 2017.   

CENTRO DE PROCESSAMENTO DE DADOS DA UNIVERSIDADE DE BRASÍLIA. Sobre o CPD. Disponível em: <[http://www.cpd.unb.br/sobre-o-cpd](http://www.cpd.unb.br/sobre-o-cpd)>. Acesso em 20 março de 2017.  

W3Schools. Browser Statistics - The Most Popular Browsers. Disponível em: <[https://www.w3schools.com/browsers/default.asp](https://www.w3schools.com/browsers/default.asp)>. Acesso em 14 de abril de 2017.

## 2. Posicionamento  

### 2.1. Oportunidade de Negócios  

<p align ="justify">O Campus Darcy Ribeiro é o mais antigo da Universidade de Brasília. Com o seu crescimento e criação de novos cursos, o número de pessoas que o circulam ficou cada vez maior e com isso a localização interna se tornou um problema. Segundo dados da universidade, mais de 50 mil pessoas frequentam diariamente o campus tendo mais de 500 mil m² de área construída. A plataforma web de mampeamento das instalações do campus Darcy Ribeiro veio com o propósito de auxiliar estudantes, servidores e visitantes da universidade facilitando a sua locomoção traçando trajetos pelos prédios.    

### 2.2. Instrução do Problema 

| O problema seria      | A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro,      |
|-----------------------|---------------------------------------------------------------------------------------------------|
| afeta                 | estudantes, servidores e visitantes da universidade,                                              |
| cujo impacto é        | a demora para encontrar e chegar à determinado lugar na universidade,                             |
| uma boa solução seria | uma plataforma web que fornece as informações de localização de salas e prédios dentro do campus. |

### 2.3. Instrução de Posição do Produto  

<p align ="justify">o "Onde é UnB?" é um serviço de localização dentro do campus que pretende auxiliar os diversos frequentadores da UnB a encontrar edifícios, departamentos, salas. Atualmente os usuários contam com opções como o Google Maps, esta, porém, se limita a localização de prédios maiores, não sendo possível receber maiores detalhes destes.  

| Para          | Estudantes, servidores e visitantes da universidade                                                                    |
|---------------|------------------------------------------------------------------------------------------------------------------------|
| Que           | desejam facilitar sua locomoção entre instalações do Campus Darcy Ribeiro                                              |
| O             | "Onde É? UnB"                                                                                                                |
| Que           | é uma plataforma web                                                                                                   |
| Diferente de  | mapas avulsos da universidade                                                                                            |
| Nosso produto | Possibilita a localização de edifícios, departamentos, salas do Campus Darcy Ribeiro pertencente a Universidade de Brasília |

## 3. Envolvidos e Usuários  

### 3.1. Resumo dos Envolvidos   

| Nome                        | Representa                                                                                                               | Função                                                                                                                                               |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Equipe de Desenvolvedores   | Grupo de discentes da Universidade de Brasília que estão matriculados na matéria Métodos de Desenvolvimento de Software. | Desenvolver e implementar a ferramenta web apresentada neste documento.                                                                              |
| Equipe de Gestão do Projeto | Grupo de discentes da UnB que estão matriculados na matéria Gestão de Portfólio de Projeto.                              | Desenvolver a aplicação web apresentada visando a detecção de possíveis riscos futuros, problemas e soluções viáveis para a conclusão deste projeto. |
| Diretoria do CPD - UnB               | Diretores do CPD        | Fornecer os dados necessários para o desenvolvimento e implementação da aplicação aqui apresentada.|
| Coaches               | Orientadores do projeto        | Orientar a equipe de desenvolvimento e a equipe de gestão no que refere a execução do projeto.|
| Professor               | Avaliador e orientador do projeto.   | Avaliar o produto e o cumprimento dos métodos de desenvolvimento utilizados e orientar as equipes quanto a execução do projeto.|  

### 3.2. Resumo do Usuário  

| Nome         | Descrição                                                                                                                                                                 |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Novos alunos | Novos aprovados na UnB que nunca tiveram contato com o Campus Darcy Ribeiro.                                                                                              |
| Palestrantes | Pessoas de fora do Campus Darcy Ribeiro convidadas a ministrar algum tipo de palestra dentro do próprio e que não possuem conhecimento sobre suas localidades.            |
| Candidatos   | O Campus Darcy Ribeiro constantemente é local de provas de concursos, vestibulares e afins. Alguns destes também não possuem conhecimento sobre as localidades do campus. |
| Visitantes   | Pessoas que desejam conhecer as instalações do Campus Darcy Ribeiro e nunca estiveram em suas instalações.                                                                |

### 3.3. Perfis das Partes Interessadas  

#### 3.3.1. Equipe de Gestão de Projeto   

| Representantes        | Alexandre Torres Kryonidis, Daniel Moura da Silva, Eduardo Brasil Martins, Eduardo Quintino Gomes, Matheus Mello e Rafael dos Santos Rabetti.                                                                                                                     |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Gerentes do projeto.                                                                                                                                                                                                                                                   |
| Tipo                  | Grupo de discentes da Universidade de Brasília que estão matriculados na matéria Gestão de Portfólio de Projeto.                                                                                                                                   |
| Responsabilidades     | Gerir a equipe visando a entrega da ferramenta web aqui proposta de acordo com as metas e propostas entregues por eles.                                                                                                                            |
| Critérios de Sucesso  | Fazer com que o grupo de desenvolvedores possua um conhecimento uniforme, trabalhe bem em equipe. Seguir de forma correta um projeto de desenvolvimento de software visando a entrega, no prazo, de uma aplicação com um ótimo nível de qualidade. |
| Envolvimento          | Alto.                                                                                                                                                                                                                                              |
| Comentários/Problemas | Uma equipe de alunos que tem o objetivo de gerir uma equipe de outros alunos com a finalidade de entregar o produto. |

#### 3.3.2. Equipe de Desenvolvedores
| Representantes        | Jordan de Oliveira Miranda, Kairon Velozo, Lucas Soares Souza, Mateus Vieira da Silva Roriz, Sannya Santana de Arvelos, Stéfane Bogéa de Souza e Taynara de Jesus Carvalho. |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Desenvolvedores do projeto.                                                                                                                                                 |
| Tipo                  | Grupo de discentes da Universidade de Brasília que estão matriculados na matéria Métodos de Desenvolvimento de Software.                                                    |
| Responsabilidades     | Desenvolver, testar, implementar a aplicação neste documento apresentada.                                                                                                   |
| Critérios de Sucesso  | Fornecerem o software de acordo com o que foi estipulado pelo cliente e pela equipe da Gestão de Projeto.                                                                   |
| Envolvimento          | Alto.                                                                                                                                                                       |
| Comentários/Problemas | Trabalhar com ferramentas nunca, ou pouco, utilizadas pela a equipe para a implementação do projeto.                                                                        |


#### 3.3.3. Diretoria do CPD UnB

| Representante         | Felipe Santos.                                                                                               |
|-----------------------|--------------------------------------------------------------------------------------------------------------|
| Descrição             | Representante do CPD UnB                                                                                     |
| Tipo                  | Cliente do projeto.                                                                                          |
| Responsabilidades     | Fornecer os dados necessários para a conclusão da aplicação.                                                 |
| Critérios de Sucesso  | Receber um software que seja capaz de orientar as pessoas que precisam localizar instalações no Campus Darcy Ribeiro. |
| Envolvimento          | Alto                                                                                                        |
| Comentários/Problemas | Conseguir fornecer um grande número de dados para a conclusão do projeto.                                    |

O nível de envolvimento das partes interessadas no desenvolvimento da aplicação é classificado da seguinte forma:  
Alto: O usuário poderá acessar todas as informações administrativas do sistema.  

### 3.4 Perfil dos Usuários  

#### 3.4.1 Novos Alunos  

| Representantes        | Novos Alunos                                                                     |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Alunos que acabaram de ingressar na Universidade de Brasília e que nunca tiveram contato com o Campus Darcy Ribeiro                               |
| Tipo                  | Usuário Informal.                                                                                                         |
| Responsabilidades     | Acessar a aplicação e utilizar os recursos para usuários comuns.                                                                    |
| Critérios de Sucesso  | Conseguir, intuitivamente, acessar todos os recursos da aplicação web.                                                                                |
| Envolvimento          | Baixo.                                                                                                                    |
| Comentários/Problemas | Pelo Campus Darcy Ribeiro ser muito extenso por muitas vezes se torna complicado se localizar dentro de suas instalações. |

#### 3.4.2 Palestrantes

| Representantes        | Palestrantes                                                                   |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Pessoas de fora do Campus Darcy Ribeiro convidadas a ministrar algum tipo de palestra dentro do próprio e que não possuem conhecimento sobre suas localidades.                              |
| Tipo                  | Usuário Informal.                                                                                                         |
| Responsabilidades     | Acessar a aplicação e utilizar os recursos para usuários comuns.                                                                    |
| Critérios de Sucesso  | Conseguir, intuitivamente, acessar todos os recursos da aplicação web.                                                                                |
| Envolvimento          | Baixo.                                                                                                                    |
| Comentários/Problemas | Pelo Campus Darcy Ribeiro ser muito extenso por muitas vezes se torna complicado se localizar dentro de suas instalações. |

#### 3.4.3 Visitantes

| Representantes        | Visitantes                                                                   |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Pessoas que por alguma eventualidade precisam se localizar pelas instalações do Campus Darcy Ribeiro.                              |
| Tipo                  | Usuário Informal.                                                                                                         |
| Responsabilidades     | Acessar a aplicação e utilizar os recursos para usuários comuns.                                                                    |
| Critérios de Sucesso  | Conseguir, intuitivamente, acessar todos os recursos da aplicação web.                                                                                |
| Envolvimento          | Baixo.                                                                                                                    |
| Comentários/Problemas | Pelo Campus Darcy Ribeiro ser muito extenso por muitas vezes se torna complicado se localizar dentro de suas instalações. |

#### 3.4.4 Candidatos

| Representantes        | Candidatos                                                                   |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------|
| Descrição             | Candidatos de provas e concursos que possuem pouca ou nenhuma familiaridade com o campus Darcy.                               |
| Tipo                  | Usuário Informal.                                                                                                         |
| Responsabilidades     | Acessar a aplicação e utilizar os recursos para usuários comuns.                                                                    |
| Critérios de Sucesso  | Conseguir, intuitivamente, acessar todos os recursos da aplicação web.                                                                                |
| Envolvimento          | Baixo.                                                                                                                    |
| Comentários/Problemas | Pelo Campus Darcy Ribeiro ser muito extenso por muitas vezes se torna complicado se localizar dentro de suas instalações. |

Os níveis de envolvimento são classificados da seguinte forma:  

Baixo: O usuário poderá visualizar as informações disponíveis nas páginas de livre acesso.  


### 3.5 Principais Necessidades da Parte Interessada ou do Usuário   

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

As prioridades são classificadas da seguinte forma:    
Alta: essencial para o usuário;  
Média: de média importância para o usuário;  
Baixa: de baixa importância para o usuário.


## 4. Visão Geral do Produto

### 4.1. Perspectiva    

<p align ="justify">Uma aplicação web com mapa capaz de auxiliar os usuários a localizar instalações tais como prédios, departamentos e salas no Campus Darcy Ribeiro da UnB. Além disso, os usuários podem visualizar trajetos entre pontos, facilitando seu deslocamento dentro do campus.</p>

### 4.2 Benefícios     

| Benefício para o Cliente                   | Recursos do Suporte                                                                                |
|--------------------------------------------|----------------------------------------------------------------------------------------------------|
| Interface gráfica        | O sistema contará com uma interface gráfica que facilitará a utilização do sistema. |
| Linguagem Simples | As formas de uso da aplicação seguirão um padrão que dará maior fluidez à sua utilização. |
| A página inicial da aplicação possuirá um menu com todos os recursos, não-administrativos, do sistema, assim, facilitando o acesso de tais ferramentas. |

### 4.3. Licenciamento  
 
<p align ="justify"> O serviço será de livre acesso e as informações serão públicas. Não haverá necessidade de instalação de aplicativos. </p>

## 5. Requisitos  

### 5.1 Requisitos Funcionais  

| Identificação | Requisito | Descrição | Prioridade |
|---------------|-----------|-----------|------------|
| RF01          | Pesquisa de pontos | O sistema deverá permitir a busca de locais do campus, como por exemplo: edifícios, departamentos e salas | Alta |
| RF02          | Traçar Rotas | O sistema deverá traçar rotas de locomoção entre dois pontos do campus | Alta |
| RF03          | Mostrar Informações de Pontos | O sistema deverá mostrar as informações do ponto selecionado pelo usuário. | Alta |
| RF04          | Mostrar Disciplinas por Sala | Quando o usuário selecionar uma sala o sistema deverá mostrar as disciplinas ministradas na sala. | Média |

As prioridades dos requisitos funcionais são definidas como:  
Alta: Recurso necessário da aplicação;  
Média: Recurso opcional da aplicação;  
Baixa: Seria bom que houvesse na aplicação.

### 5.2 Requisitos Não Funcionais

| Identificação | Descrição | Prioridade |
|---------------|-----------|------------|
| RNF01         | O sistema deve funcionar nos navegadores mais utilizados do mercado, tais como Firefox e Chrome. | Alta |
| RNF03         | O sistema deverá ter interface responsiva, para que o usuário consiga usá-lo dispositivos móveis. | Alta |
| RNF04         | O sistema deverá estar em português. | Média |

As prioridades dos requisitos não funcionais são definidos como:  
Alta - Essencial para o correto funcionamento da apliação;  
Média - Auxilia na melhora da experiência do usuário da aplicação;    