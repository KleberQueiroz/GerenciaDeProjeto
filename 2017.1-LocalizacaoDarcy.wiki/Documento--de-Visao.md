## Histórico de Revisões

|    Data    | Versão |     Descriçao     |   Autor   |
|:----------:|:------:|:-----------------:|:---------:|
| 16/03/2017 |   1.0  | Iniciando Doc.    | Lucas S.  |

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

  
[04) Visão Geral do Produto](#04-visão-geral-do-produto)  
[05) Recursos do Produto](#05-recursos-do-produto)  
[06) Restrições](#06-restrições)  
[07) Faixas de Qualidade](#07-faixas-de-qualidade)  
[08) Precedência e Prioridade](#08-precência-e-prioridade)

------

## 1. Introdução
Este documento tem o objetivo de apresentar uma visão completa sobre o software de mapeamento das instalações e de localização do Campus Darcy Ribeiro da Universidade de Brasília (UnB).

Espera-se que o leitor deste documento consiga compreender a finalidade global da aplicação UnbMapa. 

### 1.1. Propósito

O Software tem como propósito facilitar a locomoção entre as instalações do Campus Darcy Ribeiro da UnB, bem como a fácil localização de salas e outras dependências.

### 1.2. Escopo

O Centro de Informática da Universidade de Brasília (CPD), é um órgão complementar da UnB que possui como intuito desenvolver as atividades de caráter permanente de apoio da pesquisa e da extensão ao desenvolvimento de ensino no que se refere ao processamento de dados, cujo os objetivos são: promover e incentivar a informática na UnB, desenvolver, implantar e manter sistemas de mainframe e em microcomputadores e supervisionar, coordenar e controlar as atividades relacionadas com pesquisas referentes a hardware, software e rede de teleprocessamento.

O UnbMapa tem a finalidade de desenvolver o software de localização, via mapa, de algumas das instalações do Campus Darcy Ribeiro da UnB bem como de alguns de seus estabelecimentos.

### 1.3. Definições, acrônimos e abreviações



### 1.4. Referências 

UNIVERSIDADE DE BRASÍLIA. Institucional. Disponível em: <[http://www.unb.br/a-unb?menu=423](http://www.unb.br/a-unb?menu=423)>. Acesso em 20 março de 2017.

CENTRO DE PROCESSAMENTO DE DADOS DA UNIVERSIDADE DE BRASÍLIA. Sobre o CPD. Disponível em: <[http://www.cpd.unb.br/sobre-o-cpd](http://www.cpd.unb.br/sobre-o-cpd)>. Acesso em 20 março de 2017.

## 2. Posicionamento

### 2.1 Oportunidade de Negócios

O Campus Darcy Ribeiro é o mais antigo da Universidade de Brasília. Com o seu crescimento e criação de novos cursos, o número de pessoas que o circulam ficou cada vez maior e com isso a localização interna se tornou um problema. Segundo dados da universidade, mais de 50 mil pessoas frequentam diariamente o campus tendo mais de 500 mil m² de área construída. A plataforma web de mapeamento das instalações do campus Darcy Ribeiro veio com o propósito de auxiliar estudantes, servidores e visitantes da universidade facilitando a sua locomoção traçando trajetos pelos prédios.

### 2.2 Instrução do Problema 

| O problema seria      | A dificuldade das pessoas de se localizarem pelos edifícios e salas no campus Darcy Ribeiro,      |
|-----------------------|---------------------------------------------------------------------------------------------------|
| afeta                 | estudantes, servidores e visitantes da universidade,                                              |
| cujo impacto é        | a demora para encontrar e chegar à determinado lugar na universidade,                             |
| uma boa solução seria | uma plataforma web que fornece as informações de localização de salas e prédios dentro do campus. |

### 2.3 Instrução de Posição do Produto  


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

### 3.4. Perfis das Partes Interessadas

#### 3.4.1. Equipe de Gestão de Projeto

#### 3.4.2. Equipe de Desenvolvedores

#### 3.4.3. Diretoria do CPD UnB

### 3.5 Perfis do Usuário

### 3.6 Principais Necessidades da Parte Interessada ou do Usuário 

|     Necessidade     |     Prioridade     |     Interesses     |     Solução atual     |     Solução proposta     |
|:-------------------:|:------------------:|:------------------:|:---------------------:|:------------------------:|


## 04) Visão Geral do Produto

### 4.1 Perspectiva do Produto:

### 4.2 Resumo das Capacidades: 


|          Beneficios para o Cliente          |          Recursos de Suporte          |
|:-------------------------------------------:|:-------------------------------------:|


### 4.3 Suposições e Dependências:

### 4.4 Custo e Precificação: 

### 4.5 Licenciamento e Instalação: 


## 05) Recursos do Produto

(citar recursos)

### Recurso 1:
### Recuros 2:


## 06) Restrições



## 07) Faixas de Qualidade



## 08) Precedência e Prioridade



## 09) Outros Requisitos do Produto

### 9.1 Padrões Aplicáveis:

### 9.2 Requisitos do Sistema:

### 9.3 Requisitos de Desempenho:

### 9.4 Requisitos Ambientais: