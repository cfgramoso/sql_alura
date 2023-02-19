Esse projeto é para colocar em pratica o curos de PostgreSQL da Alura.

Fazer a instação do PostgreeSQL (versão 12) e pgAdmin (versão 4);
Link: https://www.postgresql.org/

No prompt de comando do SQL Shell (psql) criar um banco de dados utilizando o comando: "CREATE DATABASE alura2;"
No PgAdmin conectar no PostgreSQL12 clicar com o botão esquerdo do mouse e clicar em Create > Database, e colocar o nome.

E comando de criar o banco de dados:
CREATE DATABASE aluna2
    WITH 
    OWNER = postgres
    ENCODING = 'UTF8'
    CONNECTION LIMIT = -1;
    
Comando para excluir o banco de dados DROP DATABASE teste;

Para saber sobre campos numericos: https://www.postgresql.org/docs/12/datatype-character.html

Tipos de campo que será utilizado:
integer
real
serial
numeric
varchar(n)
char(n)
text
boolean
date
time
timestamp


