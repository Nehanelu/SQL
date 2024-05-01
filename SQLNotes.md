-SQL(Structure Query language  )are used to store query and manipulate data

-Data base :A data base is a collection of information
-Queries for data base
1 Create database DataBaseName;
(it is use to create data base)
2 Drop database DataBaseName;
(deletes the database from an instance of SQL Server and deletes the physical disk files used by the database.)
3 Backup database DataBaseName;
(A copy of SQL Server data that can be used to restore and recover the data after a failure.)

-SQL COMMANDS

DDL (data defination language)
1 Create: Used to create a new table in the data base
2 drop : used to delete the structure and record store in th table
3 alter : Used to alter contents of a table by adding some new column or attribute, or changing some existing attribute.
4 Truncate: Used to delete all the rows from the table and free up the space in the table

DML (data Manipulation language):It is used for modifying a database, and is responsible for any form of change in a database. 
1 Insert :Used to  insert data in the row of a table.
2 Update :Used to update value of a table column
3 Delete : used to delete one or more rows in a table
DCL (Data control language):These commands are used to grant and take back access/authority (revoke) from any database user.
1 Grant :Used to grant a user access privileges to a database
2 Revoke :Used to revoke the permission from an user
TCL(Transition control language):These commands can be used only with DML commands in conjunction and belong to the category of auto-committed commands.
1 Commit:Saves  all the transactions made on a database.
2 Roll back:It is  used to undo transactions which are not yet been saved.
3 Save point :used to roll transaction back to a certain point without having to roll back the entirity of the transaction.
DQL(Data Query language)
1 Select :It is used to fetch some data from a database. 

-Constrain 

1 Not Null
2 Unique
3 primary key
4 foreign key
5 check
6 default
7 create index

-Curd Operation in sql

1 create : insert
2 Read :Select
3 Update : Update
4 delete :Delete

-Clauses in sql

1 Where:Used to select data from database based on some conditions
2 And: the and operator display a record if all condition true
3 Or : the or operator display a record if any condition true
4 Like : used to search for a specified pattern in a column
5 Limit : puts a restriction on how many rows are returned from a query
6 Orderby : keyword is used to store the result-set in ascending or descending order
7 GroupBy:group rows that have the same values into summary rows
8 Having: it performs the same as the WHERE clause but can also be used with aggregate function.

-Operators 
 = equal,>less,<= less equal ,> greater ,>=greater equal , <> not equal
 between (between certain range)
 like (search for pattern)
  
  -SQL Aggregate Function
  Min(),Max(),Count(),Sum(),Avg()

-Keys
Primary Key: (unique ,NotNull) 
foregin Key :(Foregin keys are keys that reference the primary keys of some other table)

-Types of Joins 
inner join
outer join
full join

