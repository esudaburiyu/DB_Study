

#用意
~~~~~
create table goods(id int , name text);
insert into goods (id, name) values (1, "goods1");
insert into goods (id, name) values (2, "goods2");
insert into goods (id, name) values (3, "goods3");
insert into goods (id, name) values (4, "goods4");

create table sheet(id int, date text, class int);
insert into sheet(id, date, class) values (1, "1/1", 1);
insert into sheet(id, date, class) values (1, "1/2", 1);
insert into sheet(id, date, class) values (1, "1/2", 2);
insert into sheet(id, date, class) values (2, "1/5", 2);
insert into sheet(id, date, class) values (3, "1/4", 1);
insert into sheet(id, date, class) values (3, "1/5", 2);
insert into sheet(id, date,class) values (4, "1/2", 2);
~~~~~