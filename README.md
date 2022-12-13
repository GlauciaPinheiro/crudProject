
SCRIPT Do BANCO DE DADOS
~~~sql
create database CadastroPessoa;

use CadastroPessoa;

create table CadastroPessoa(
      id_Pessoa INT PRIMARY KEY auto_increment,
      nome_Pessoa varchar (150) not null, -- o funcionario não pode ser nulo
      CPF_Pessoa varchar (11) not null -- o sobrenome não pode ser nulo
      RG_Pessoa varchar (10) not null,
      CEP_Pessoa varchar (10) not null
);      

describe funcionario;

insert into Pessoa(IdPessoa, NomePessoa, CPFPessoa, RGpessoa, CEPpessoa)
values (
 1, "glaucia",58263897245, 38623416,  45678912,
 2, "joao", 34628612398,  78965432,  12345678,
 3, "gladson",  73698523614, 12345678,  98765432,
 4, "julianderson",  65498732158,  34567891, 29874563
 );
 ~~~
