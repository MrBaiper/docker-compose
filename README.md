# docker-compose

1- docker-compose up
2- docker exec -it mysql bash
3- mysql -u root -p
4- password: ==> root

5- create database personas;
use personas;
create table persona (
    id int (3) unsigned auto_increment primary key,
    nombre varchar(50) unique,
    fecha date
);
