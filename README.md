# Create table Script
create table sourcetable (
id int identity(1,1),
name varchar(50),
village varchar(50)
)

create table targettable (
id int identity(1,1),
name varchar(50),
village varchar(50),
createdon datetime,
createdby varchar(20),
modifiedon datetime,
modifiedby varchar(20)

)

insert into sourcetable (name,village)
values ('Gaurang','patdi'),('Nilesh','Goraiya')
