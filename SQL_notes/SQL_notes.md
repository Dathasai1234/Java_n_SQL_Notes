# Application

Set of programs which are compressed together to perform specific tasks is known as application.

1. Stand alone applications. (internet not required)
2. Web applications. (can be used in web)
3. Client server application. (Only can be used as an application by installing.)

---

# SQL

## Structured Query Language.

1. SQL is a language which is used to communicate with database.

- Communicating in the form of.
  1. Create or insert
  2. Read or retrieve
  3. Update or modify
  4. Delete or drop

---

# DataBase

## Data

- Data which (values) determines the properties of an entity.
- Data is the value which is going to determine the properties of an any entity.

(or)

- Data is a files which determines the attributes of any entity.

* Attributes -----> Properties

  Entity -----> Living or non living entity.

## Database

Database is a place where we can store information.

![Alt text](Assets/1.%20DB.jpg)

---

# Database management system.

It is a software which is used to maintain and manage the database.

- Database will provide 2 features.

  1. Security.
  2. Authority.

- DBMS stores all the data in the form of `file format`.
- To communicate with DBMS we have to use `query language`.

![Alt text](<Assets/2.%20DBMS%20(1).jpg>)

---

# Relational database management system.

![Alt text](Assets/3.%20RDBMS.jpg)

- Any software which stores data in the form of table is known as RDBMS.
- To interact with RDBMS we have to use SQL.

![Alt text](Assets/4.%20table.jpg)

---

# Tables

The logical alignment of rows and the columns is known as tables.

## Rows

The horizontal alignment of the lines, known as rows.

## Columns.

Vertical alignment of the lines, known as columns.

## Cell

This molest part of the table known as seller or the interaction part of the rows and columns is known as cells.

---

# Validation.

This is a process of checking the data before entering into the column. There are 2 ways of validation.

1. Data types.
2. Constraints.

## Data types.

There are 5 types of data types.

1. `CHAR()`
2. `VARCHAR()`
3. `Date`
4. `Number`
5. Large Object
   - `Character Large Object` (CLOB)
   - `Binary Large Object` (BLOB)

---

# DataTypes

## CHAR()

Can Store uppercase alphabets, lower case alphabets, special character (@, #, $, !), alphanumeric, digits in single quotes.

## Syntax

> CHAR(SIZE)

- Size --> Neumeric value

- Example

  - `CHAR(10)`

  - 10 digits of characters.

  - `Size` stores up to 2000 bits.

- The maximum capacity of CHAR data type is up to 2000 bits.

- It follows a fixed length of memory allocation.

- Character data type we can use whenever we want to store `fixed size` of data.

- Example
  - Pan card number.
  - Voter ID number.
  - Passport number ECT.

| R   | A   | M   |     |     |     |
| --- | --- | --- | --- | --- | --- |

- RAM is Used memory and remaining is waste memory.

---

## VARCHAR()

Same as a CHAR data type. Stores upper case Alphabets , lower case alphabets, special characters, Alphanumeric values.

## Syntax

> VARCHAR(SIZE)

- Size --> Neumeric value

- Example

  - `VARCHAR(20)`

  - 20 digits of characters.

- It follows variable length of memory allocation.

- Here the unused memory subtracted and returned to the maximum size of the VARCHAR (Original memory).

- VARCHAR data type is used to store variable size of data.

- Size is not fixed.

| R   | A   | M   |
| --- | --- | --- |

- Only memory is used. No memory wastage.

---

## VARCHAR2()

This data type will double the size of normal data type.

- VARCHAR2(200) ---> Size = 400

---

## DATE

- It is used to store any type of Dates.
- To store the dates, Oracle Company has given 2 formats.

  - DD-Mon-YY
  - DD-Mon-YYYY

- Date always will be mentioned within single quotes.

- Example

  - '06-APR-23'
  - '06-APR-2023'

---

## Large object.

- It is used to store huge amount of data.
- The maximum capacity of large object is up to 4 GB.
- There are 2 types of large object.
  - Character large object CLOB.
  - Binary large object BLOB.

### CLOB.

- This data type is used to store huge amount of `characters` type of data.
- Maximum capacity of CLOB is 4G.
- 1 GB is equal to 64,000 characters.
- 4 GB is equal to 2,56,000 characters.

### BLOB.

- This is used to store huge amount of `file` type of data.
- Maximum capacity of BLOB is 4 GB.
- Example
  - Photos.
  - Videos.
  - Audio.
  - PDFs.
  - Documents Etcetera.

---

## Number()

It is used to store any numeric value that are integers and decimals.

### Syntax

> NUMBER(Precision, [Scale])

- Square brackets in SQL are used For those properties which can be an optional properties.

### Precision

It is used to determine the number of digits that are required to store any integer value.

- Limit or Range - `01` to `38`.

### Scale

It is used to determine the number of digits which are required to store for the decimal value within appreciation.

- The range of scale is `-84` to `127`

- Example
  - Number(3) ===> +-999
  - Number(3, 2) ===> +-9.99
  - Number(3, 3) ===> +-999
  - Number(4, 5) ===> +-.09999
  - Number(4, -2) ===> +-9999.00
