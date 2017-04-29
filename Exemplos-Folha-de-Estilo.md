Do's and Dont's Javascript

// Faça isso 
const atom = { 
  value: 1,

  addValue: function (value) {
    return atom.value + value;
  },
};

// Não faça isso, vai quebrar o heroku 
const atom = {
  value: 1,

  addValue(value) {
    return atom.value + value;
  },
};



Do's and Dont's Ruby on rails

//Prefira  essa sintaxe quando for declarar
find('.navbar-title', text:  'Dashboard')
//Do que essa 
find('.navbar-title', :text => 'Dashboard')

//Usar aspas simples quando não estiver usando caracteres especiais ou interpolação de strings

//Prefira assim
fill_in 'admin_password', :with => password
//Do que assim
fill_in "admin_password", :with => password

