# Variable Types #


Variables are for storing information the database requires you to define the information your storing into types. Depending on the database they are called different but the usually have the basic types:
These types include:

* Integer (Whole Numbers)
* REAL (whole + fractional, decimal, float)
* Text (String values, characters, numbers for non math calculations
* BLOB (RAW Data, binary, GIFS, PNGS, executables bytes (examples)

# Create Table #

Syntax on how to create a table:
* CREATE TABLE users(id INTEGER PRIMARY KEY AUTOINCREMENT, username TEXT, password TEXT, enabled INTEGER);
* The ID is for indexing usually for storing each record and for mapping with other tables
* Username (data column for users)
* Password (for authentication)

# Insert Records # 

*Using the insert command (storing values in database):
  * Insert into tablename(colnam1,colname2,colname3)  values(…..)
    * Example:
      *  insert into users(username,password,enabled) values('david','passwordtogointo',1);
      *  insert into users(username,password,enabled) values('renchie','passwordtogointo',1);
     
 # Retrieval Values:

* You retrieve values using select statements:
  * All rows:
     * Select * from table;
     * Select * from users;
     * sqlite> Select * from users;
   
  *Specific rows using condition statement where:
     * Select * from table where columname = ‘value’
     * Select * from table where columname = number

     * Select * from users where username = 'david';
     * Select * from users where id = 1;
    
  * Selecting certain columns:
      * Select columnname where columnname = ‘value’;
      * select password from users where username = 'david';
      results:
         passwordtogointo

