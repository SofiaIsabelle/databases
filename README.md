# What is a database ?
A database is a structured set of data held in a computer, especially one that is accessible in various ways.

# What are relational databases?
A database structured to recognize relations among stored items of information

# How are relational databases different from XML?
When you design your databases you must decide if your whether your data is better suited for the XML model or the relational model.

1) XML data is hierarchical , relational data is represented in a model of logical relationships. An XML document contains information 
about the relationship of data items to each other in the form of the hierarchy. With the relational model, the only types of 
relationships that can be defined are parent table and dependent table relationships.

2) XML data is self describing ; relational data is not.
An XML document contains not only the data, but also tagging for the data that explains what it is. A single document can have different types of data.
With the relational model, the content of the data is defined by its column definition. All data in a column must have the same type of data.

3) XML data has inherent ordering; relational data does not.
For an XML document, the order in which data items are specified is assumed to be the order of the data in the document. 
There is often no other way to specify order within the document. For relational data, the order of the rows is not guaranteed 
unless you specify an ORDER BY clause on one or more columns.

# What is SQL ?
SQL is a domain-specific language used in programming and designed for managing data held in a relational database management system,
or for stream processing in a relational data stream management system.

# What is SQL used for ?
SQL stands for Structured Query Language. SQL is used to communicate with a database. It is the standard language for relational 
database systems.

# What does CRUD stand for ?
C:reate  R:ead  U:pdate D:elete

# Why is the idea of CRUD so important for web apps ?
CRUD is a backronym that describe all of the functions that can be done that can be done to data that is being stored 
within a database or application. As previously stated these functions include Create, Retrieve, Update, and Delete. Without all four 
of these functions , an application is incomplete and will not function properly.

# How do you get all the records from a table in SQL?
The SELECT statement is used to select data from a database.
The data returned is stored in a result table, called the result-set.

# How do you insert a record in SQL?
The INSERT INTO statement is used to insert new records in a table.
INSERT INTO Syntax :

* INSERT INTO table_name (column1, column2, column3, ...)
  VALUES (value1, value2, value3, ...);

* INSERT INTO table_name
  VALUES (value1, value2, value3, ...);


# What is a primary key?

A primary key, also called a primary keyword, is a key in a relational database that is unique for each record. It is a unique 
identifier, such as a driver license number, telephone number (including area code), or vehicle identification number (VIN). A 
relational database must always have one and only one primary key.

# What is a foreign key?
In the context of relational databases, a foreign key is a field in one table that uniquely identifies a row of another table or 
the same table.# databases
