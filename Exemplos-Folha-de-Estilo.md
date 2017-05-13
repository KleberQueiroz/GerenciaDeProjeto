## Histórico de Versões

| Data  | Versão | Descrição                  | Autor(es)     |
|-------|--------|----------------------------|---------------|
| 29/04 | 0.1    | Criação do documento.      | Mateus Roriz  |

## Introdução

Este documento contém exemplos de código de acordo com a folha de estilo, usada durante o desenvolvimento da aplicação _Onde É? UnB_.

## Do's and Dont's Javascript

 Faça isso 
```javascript
const atom = { 
  value: 1,

  addValue: function (value) {
    return atom.value + value;
  },
};
```
 Não faça isso, vai quebrar o heroku 
```javascript
const atom = {
  value: 1,

  addValue(value) {
    return atom.value + value;
  },
};
```

## Do's and Dont's Ruby on rails

Usar aspas simples quando não estiver usando caracteres especiais ou interpolação de strings

Prefira assim
```ruby
fill_in 'admin_password', :with => password
```
Do que assim
```ruby
fill_in "admin_password", :with => password
```
Prefira  essa sintaxe quando for declarar
```ruby
find('.navbar-title', text:  'Dashboard')
```
Do que essa 
```ruby
find('.navbar-title', :text => 'Dashboard')
```
