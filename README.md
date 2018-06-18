# db_connection
Databases
* Databse insert

insert into tableName(
id,Name,roll,regestion,address) values (3.'sujan','5',564,feni Devipur);


*Upadte Database

update TableName set name ='sujan' where id =1


* dalete Database

dalete from tableName where id =3;

* Delete all table data command

truncate table tableName;


**multifal data insert run

Begin 

insert into Table (Id,name,roll,regestition,address) values (1,'sujan','5,56,Feni Debipur);
insert into Table (Id,name,roll,regestition,address) values (2,'lition','6,57,Feni Debipur);
insert into Table (Id,name,roll,regestition,address) values (3,'sanjoy','7,58,Feni Debipur);
insert into Table (Id,name,roll,regestition,address) values (4,'rakib','8,59,Feni Debipur);
insert into Table (Id,name,roll,regestition,address) values (5,'anik','9,60,Feni Debipur);
insert into Table (Id,name,roll,regestition,address) values (6,'ayon','10,61,Feni Debipur);
insert into Table (Id,name,roll,regestition,address) values (7,'rajib','11,62,Feni Debipur);
insert into Table (Id,name,roll,regestition,address) values (8,'anima','12,63,Feni Debipur);
End;


***multiful update 
update tableName set name = 'akash' where id in (1,5,8);
update tablename set gende= 'akbor' where i in (1,2,3);


***Delete mulful 

Delete from tablename where id in (1,3,9);

delete from tablename where id



 1.MAKE FORENKEY -alter table Empoloye add constraint cons_employee_fk Foreign key (GenderID) referances Gender (id)
2.DELETE FOREIGN KEY- Drop employe constraint cons_employee_fk


* Primary key:

create table EmployType(
id int not null Primary key,
Employ_name varcher(50) not null,
Employ_Address varcher (50) 
employTypeId int
);



* defautl constraint

1.alter table Employe
add constraint (constraing_name) employeeTypeIs_DefaultCons
Default 2 for EmployeeTypeId


insert into Empoyee(id,Name,Email,GenderId,) valuse (5,'a@gmail.com', 'mail')


* Cascading referential integrity constraint

** Part 10
Select record for table

	select * from tablename
		how to show fixed colume reselt

		select name from tablename

		select address from talbename

how to show fixed id ruselt

 select * from tablename whrer id =1;


** Part 11

Check constraint

Add colum ->Alter table tablename 
add columName int

show Add colum
Select * from tableName

insert data Table 

insert into tablename(
ID,name,email,age,Genderid,EmployTypeId) values(3,'sujan','a@gmail.com',1,2,-30);


add Expression or Condition

Age >0 AND Age <100


Add constriaint

Alter table tableNamea
Add Constraint ConstrainName check (Age> 0 AND AGE<100)


Delete Constraint constraintName
Drop Constrain  Emoply 


** part 12

Identity Colummm

Select * from tableName

insert into cousomer Values('sujan');

delect froem table where name/id =table id=1?


* how to set old id in new id

set indentity_insert customerName ON

Delete any Table data

->selete from tableName

how to delete hide id Number

delete table id data cmd->DBBC CHECKIDENT (TABLE_iD RESEED,0)


** Part -13

Delete and truncate

Delete->Delet any data
	Delete from tableName where (any name or id)

Truncate->
	truncate table talbeName

	-> truncate delete data in data base any id and data
	strat id 1

** Part -14
	1.last Generated row idintity
		cmd->Select SCOPE_IDENTTY()

    2.@@IDENTITY
    cmd->Select @@IDENTITY

    3.select IDEENT_CURRENT('TABLENAME')

** Part -15

   1.Unique key constraint

   cmd

   	select * from tableName

   	trsert into tableName values ('tashfiqre',123.456);

   	Alter Table Csastomer
   	Add constraint qk_coscomer_passportNO unique (PassportNo);


   	** Part -16
   	contrain summary

   	->Not null->Any colum cannot store NUll value
   	->unique-Ensure that each row for a column must have a qniqur value
   	->Primary key-
   	->Forenge key
   	_>check
   	->Default->

   	** Part -17

   	Select Statement

   	Select Specific rows
   	->select all rows
   	-Filtering with whereclause
   	->joining multiple
   	->sort rows using order by
   	select top n
   	Select top n Pecent

** part -18

sql oparator

= if the valuse of tow opa



















