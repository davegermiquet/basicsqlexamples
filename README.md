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
