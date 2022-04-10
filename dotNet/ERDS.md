# ERDS

## Data model attributes

- The DataType attribute is used to indicate a data type that is more particular than the intrinsic type of the database. We only want to keep track of the date in this situation, not the date and time. Many data types are supported by the DataType Enumeration, including Date, Time, PhoneNumber, Currency, EmailAddress, and others. The DataType attribute can also be used to enable the application to provide type-specific features automatically.

- For ASP.NET Core MVC, the StringLength attribute determines the maximum length in the database and enables client and server validation.


## DBMS - Overview

- Data is a collection of linked facts and statistics that may be processed to provide information, and a database is a collection of related data.

- A database management system stores data in such a way that it becomes easier to retrieve, manipulate, and produce information.

## DBMS Characteristics

- Real-world entity
- Relation-based tables
- Isolation of data and application
- Less redundancy
- Consistency

### what is a  database schema 
- It's an abstract design that reflects the database storage of your data. It explains the way data is organized as well as the relationships between tables in a database.

### Why do we use a database schema
- It helps developers visualize how a database should be structured.

### what does a database shcema look like
![](https://www.lifewire.com/thmb/BEHQk8ko0QaYhxWslUcHj5mXK5I=/1187x782/filters:fill(auto,1)/info-database-schema-5c6c1494c9e77c000119fc1c.jpg)


### What is a primary key in a database
- It's the column or columns in a table that have values that uniquely identify each row.

### What is a foreign key in a database
- It's a column (or a set of columns) that's used to create and enforce a link between data in two tables, limiting the amount of data that can be kept in the foreign key table.


### What is a composite key in a database
- It's a sort of primary key that creates a unique value by combining the contents of two or more fields from a table.

### What is a 1:1 relationship? 
- A single record in one table is linked to a single record in another table.

### What is a Many:Many relationship?
- When a parent row in one table has several child rows in the second table, and vice versa, it is referred to as a relationship between tables in a database.

### What is a 1: Many  relationship?
- one record in a table can be associated with one or more records in another table

### What is a Many : 1  relationship?
- It's a relationship between several instances of one entity and a single instance of another entity.