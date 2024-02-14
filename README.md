# MYSQL
show databases;
use  fivesemester;
create table lab  (rollno int,gender varchar(20),studentname varchar(30));
select * from lab;
insert into lab values('120','Male','Hanzla');
insert into lab values('121','Female','girl');
delete from lab where studentname='girl';
select * from lab;
DELETE FROM lab WHERE rollno = 121;
SELECT * FROM lab WHERE rollno = 121;
create table lab1 (rollno int not null,gender varchar(20)not null ,studentname varchar(30)not null);
select * from lab1;
create table lab1 (rollno int not null,gender varchar(20)not null ,studentname varchar(30)not null);

create table lab2(rollno int primary key not null,gender varchar(20)not null ,studentname varchar(30)not null);
insert into lab2 values('120','Male','Hanzla');
insert into lab2 values('121','Male','Hanzla');

DELETE FROM lab2 WHERE rollno = '121';
select *from lab2;
create table lab3(rollno int unique not null,gender varchar(20)not null ,studentname varchar(30)not null);
insert into lab3 values('120','Male','Hanzla');
select *from lab3;
insert into lab3 values('120','Male','Hanzla');
