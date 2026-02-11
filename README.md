
CREATE database alunos;
use alunos; 
CREATE table ESTUDANTES (id_estudante int primary key auto_increment not null,
data_nascimento date  not null,
localidade varchar(10)not null,
veiculo_proprio bit not null,
profissao varchar (100) not null
);
alter table ESTUDANTES add  column idadeint not null; 
insert into estudantes(data_nascimento,localidade, veiculo_proprio,profissao)
values (
