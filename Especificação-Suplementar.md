##Histórico de Revisões

| Data       | Versão | Descrição                                                                                                                      | Autor            |
|------------|--------|--------------------------------------------------------------------------------------------------------------------------------|------------------|
| 18/04/2017 | 0.1    | Iniciando documento de especificação suplementar, Introdução.                                                                  | Taynara Carvalho |
| 18/04/2017 | 0.2    | Escopo,,Visão Geral, Confiabilidade, Suportabilidade, Interfaces, Requisitos de Licenciamento, Usabilidade, Padrões Aplicáveis | Stéfane Souza    |
| 18/04/2017 | 0.3    | Referências                                                                                                                    | Sannya Arvelos   |
| 18/04/2017 | 0.4    | Desempenho e Restrição de Design                                                                                               | Taynara Carvalho |
| 19/04/2017 | 0.5    | Criação do Documento aqui na wiki.                                                                                             | Lucas S.         |

-------

## Índice

[1. Introdução](#1-introdução)  
&nbsp;&nbsp;[1.1. Finalidade](#11-finalidade)  
&nbsp;&nbsp;[1.2. Escopo](#12-escopo)  
&nbsp;&nbsp;[1.3. Definições, Acrônimos e Abreviações](#13-definições-acrônimos-e-abreviações)     
&nbsp;&nbsp;[1.4. Referências](#14-referências)  
&nbsp;&nbsp;[1.5. Visão Geral](#15-visão-geral)  
[2. Usabilidade](#2-usabilidade)  
&nbsp;&nbsp;[2.1. Facilidade de Uso](#21-facilidade-de-uso)  
&nbsp;&nbsp;[2.2. Mensagens de Erro](#22-mensagens-de-erro)  
[3. Confiabilidade](#3-confiabilidade)  
&nbsp;&nbsp;[3.1. Garantia de Disponibilidade](#31-garantia-de-disponibilidade)  
&nbsp;&nbsp;[3.2. Garantia de Segurança e Armazenamento de Dados](#32-garantia-de-segurança-e-armazenamento-de-dados)  
&nbsp;&nbsp;[3.3. Garantia de Segurança dos Dados Informados](#33-garantia-de-segurança-dos-dados-informados)    
[4. Desempenho](#4-desempenho)  
[5. Suportabilidade](#5-suportabilidade)  
&nbsp;&nbsp;[5.1 Suporte para Websites](#51-suporte-para-websites)      
&nbsp;&nbsp;[5.2 Suporte para Mobile](#52-suporte-para-mobile)  
[6. Restrições de Design](#5-restrições-de-design)   
&nbsp;&nbsp;[6.1 Responsividade](#51-responsividade)  
[7. Interfaces](#7-interfaces)     
&nbsp;&nbsp;[7.1 Interface de Usuário](#71-interface-de-usuario)   
&nbsp;&nbsp;[7.2 Interface de Hardware](#72-Interface-de-Hardware)   
&nbsp;&nbsp;[7.3 Interface de Software](#73-interface-de-software)   
&nbsp;&nbsp;[7.4 Interface de Comunicações](#74-interface-de-comunicações)     
[8. Requisitos de Licenciamento](#8-requisitos-de-licenciamento)    
[9. Observações Legais de Direitos Autorais Etc](#9-observações-legais-de-direitos-autorais-etc)    
[10. Padrões Aplicáveis](#10-padrões-aplicaveis)   

------

## 1. Introdução  

### 1.1 Finalidade  

<p align ="justify">O objetivo deste documento é identificar requisitos que não são retratados diretamente nas especificações de caso de uso. Entre os requisitos aqui tratados, os mais evidenciados são os requisitos não funcionais, como os requisitos legais e reguladores incluindo padrões de aplicativo, atributos de qualidade (usabilidade, confiabilidade, desempenho e suportabilidade). Outros requisitos como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design também serão especificadas neste documento.   

### 1.2 Escopo  

<p align ="justify">As especificações descritas no documento estão associadas ao projeto Onde É UnB, desenvolvida por alunos do campus Gama (FGA) da UnB das matérias MDS e GPP. uma aplicação web que tem como objetivo facilitar a localização de alunos e visitantes dentro do campus Darcy Ribeiro da Universidade de Brasília.   

### 1.3 Definições, Acrônimos e Abreviações  

<p align ="justify">1. UnB - Universidade de Brasília
<p align ="justify">2. FGA - Campus Gama da Universidade de Brasília
<p align ="justify">3. MDS - Métodos de Desenvolvimento de Software
<p align ="justify">4. GPP - Gestão de Portfólio de Projeto 
<p align ="justify">5. GNU (General Public License) - Licença Pública Geral GNU

### 1.4 Referências  

[1. Documento de Visão](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB/wiki/Documento--de-Vis%C3%A3o)  
[2. Documento de Arquitetura](https://github.com/fga-gpp-mds/2017.1-OndeE-UnB/wiki/Documento-de-Arquitetura)   
[3. Template Especificação Suplementar](http://www.funpar.ufpr.br:8080/rup/webtmpl/templates/req/rup_sspec.htm)   
Acessado em 17 de abril em 2017.  

### 1.5 Visão Geral  

<p align ="justify">O objetivo deste documento é abordar os requisitos suplementares da aplicação web, portanto os requisitos não funcionais do sistema.   

## 2. Usabilidade  

### 2.1 Facilidade de Uso  

<p align ="justify">O usuário não necessitará de treinamentos para a utilização da aplicação. Já o administrador pode passar por um treinamento básico para saber como interagir com o sistema de manutenção da aplicação.  

### 2.2 Mensagens de Erro

<p align ="justify">No caso de algum tipo de erro, o sistema deverá apresentar mensagem informando o usuário do problema.    

## 3. Confiabilidade  

### 3.1 Garantia de Disponibilidade  

<p align ="justify">A aplicação web deve funcionar 24 horas por dia, 7 dias na semana quando tiver acesso à internet.  

### 3.2 Garantia de Segurança do Armazenamento de Dados

<p align ="justify">Somente o usuário do tipo administrador terá acesso às informações de cadastro do mapa da aplicação web.   

### 3.3 Garantia de Segurança dos Dados Informados  

<p align ="justify">Não deve haver erros nas informações contidas no mapa que serão mostradas ao usuário.   

## 4. Desempenho  

<p align ="justify">* A aplicação deve suportar no mínimo 200 pessoas usando a aplicação simultâneamente.  
<p align ="justify">* As imagens de mapeamento devem ser carregadas em até 5 segundos  
<p align ="justify">* O cálculo de trajetos deve ser realizado em até 10 segundos, independentemente do modo de viagem.  

## 5. Suportabilidade  

### 5.1. Suporte para Websites  

<p align ="justify">O sistema deverá operar nos navegadores Google Chrome versão  57.0.2987.133 ou posterior, Mozilla Firefox 52.0.2 ou posterior.  

### 5.2 Suporte para Mobile  

<p align ="justify">O sistema deverá operar normalmente em navegadores nos smartphones ou tablets na versão mobile.   

## 6. Restrições de Design  

### 6.1 Responsividade

<p align ="justify">A aplicação deve se adaptar automaticamente à largura de tela do dispositivo no qual ele está sendo utilizado.  

## 7. Interfaces  

### 7.1 Interfaces de Usuário  

<p align ="justify">A aplicação web terá interfaces que são visualizadas pelo usuário de acordo com o navegador que estiver sendo utilizado.  

<p align ="justify">1. Página Inicial do Mapa  
<p align ="justify">2. Tela de Informações de Ponto no Mapa  
<p align ="justify">3. Tela de visualização do Trajeto  

### 7.2 Interfaces de Software   

<p align ="justify">1. Computador   
<p align ="justify">2. Notebook    
<p align ="justify">3. Smartphone   
<p align ="justify">4. Tablet   

### 7.3 Interfaces de Software  

<p align ="justify">1. Navegadores como Google Chrome versão 57.0.2987.133 ou posterior, Mozilla Firefox 52.0.2 ou posterior.  

### 7.4 Interfaces de Comunicação  

<p align ="justify">1. Wi-Fi  
<p align ="justify">2. Internet Móvel  

## 8. Requisitos de Licenciamento  

<p align ="justify">Essa aplicação web é um software livre, o que significa que por ser matéria MDS pode ocorrer do projeto ser continuado, redistribuído e/ou melhorado acordo com os documentos que o descrevem. A licença do software é a GNU ou GNU GPL (General Public License) desenvolvida por Richard Stallman que fundou a Free Software Foundation (FSF), uma fundação que ajuda no desenvolvimento da GNU.  

## 9. Obervações Legais de Direitos Autoraris etc  

<p align ="justify">Para o mapa foram utilizadas imagens do OpenStreetMap e bibliotecas Leaflet para adicionar funcionalidades ao mapa.  

## 10. Padrões Aplicáveis  

<p align ="justify">Padrão da Arquitetura MVC (Model - View - Controller) foi utilizado no desenvolvimento da aplicação.  



