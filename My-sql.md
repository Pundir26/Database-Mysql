#Below are the commands which needs to be executed on ClI once a azure datadase for my-sql has been created.


mysql --host=mysql-server-in28minutes.mysql.database.azure.com --user=mysqlserver -p
 
create database todos;
use todos;
create table user (id integer, username varchar(30) );
describe user;
insert into user values (1, 'Ranjith');
insert into user values (2, 'Ramesh');
select * from user;
