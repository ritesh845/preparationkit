``Basic MySQL Interview Questions``

**MYSQL**

Mysql is databases management system for web servers. 

SQL is stand for **Structured Query Language**

___

**Database**
A Database is strutured collection of data stored in computer system and organized in way to be quickly searched
___

**Advantages**

- Flexiblity 
- Power
- Full text indexing and searching
- Query Caching 
- Replication
- Configure & Security 
- Enterpirse level SQL features
    
    * views
    * stored
    * subquries
    * procedures
___


**Mysql Database Containe**

A Mysql Database contain one or more tables.
___

**Command Mysql Commands**
- ALTER
- CREATE
- DROP
- GRANT
- DESCRIBE
- INSERT
- UPDATE
- REVOKE
- USE
- BACKUP
- EXIT (CTRL + C)
- HELP
- LOCK
- QUIT
- RENAME
- SHOW
- SHOURCE
- STATUS
- TRUNCATE
- UNLOCK
- \c (Cancel input)
  
---
 
**Create a Database, Show databases, use database and drop database in mysql**

```
CREATE DATABASE IF NOT EXISTS database_name;

SHOW databases;

USE database_name;

DROP IF EXISTS database_name;
```
---

**Create table using mysql**

```
CREATE TABLE IF NOT EXISTS table_name (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(255) NOT NULL,
    description LONGTEXT NOT NULL
) ENGINE InnoDB;
```
---

**Insert data in mysql**

```
INSERT INTO table_name (colume1,colume2,colume3) VALUES (value1,value2,value3);

Example:- 

INSERT INTO table_name (id,name,description) VALUES (1,"John","I am john");
```
---

**Remove colummn from database**

```
ALTER TABLE table_name DROP IF EXISTS column
Example:-
ALTER TABLE table_name DROP IF EXISTS description
```
---

**Create index and drop index in mysql**

```
CREATE:  CREATE INDEX index_name on table_name (column1, column2, ...);

DROP : ALTER TABLE table_name DROP IF EXISTS INDEX index_name;
```
___

**Numeric datatypes in mysql**
- TINYINT       (_very small interger_)
- SMALLINT      (_small interger_)
- MEDIUMINT     (_medium interger_)
- INT           (_standard interger_)
- BIGINT        (_large interger_)
- DECIMAL       (_fixed point integer_)
- FLOAT         (_Single-precision floating point number_)
- DOUBLE        (_Double-precision floating point number_)
- BIT           (_Bit Field_)

---
**String datatypes in mysql**

Types       |  Meaning
----------- | -----------
CHAR        | fixed length nonbinary(character) string     
VARCHAR     | variable length nonbinary string (default 255)
BINARY      | fixed binary length string
VARBINARY   | variable length binary string
TINYBLOB    | 
BLOB        |
MEDIUMBLOB  |
LONGBLOB    |
TINYTEXT    |
TEXT        |
MEDIUMTEXT  |
LONGTEXT    |
ENUM        |
SET         |
NULL        |

**Temporal Data Types in MySQL?**
Type Name	| Meaning
----------- | -----------
DATE	    | A date value, in ' CCYY-MM-DD ' Format
TIME        | A Time value, in ' hh : mm :ss ' format
DATETIME    | Date and time value, in ' CCYY-MM-DD hh : mm :ss ' format
TIMESTAMP	| A timestamp value, in ' CCYY-MM-DD hh : mm :ss ' format
YEAR        | A year value, in CCYY or YY format

**What is Blob in mysql?**
Blob is an acronym that Binary long object .Blob can hold very large amount of data
example :document, images and even videos

**Add User in mysql**

```
CREATE USER `test_user` IDENTIFIED BY 'sample_password';
```


``Intermediate MySQL Interview Questions``

**VIEWS IN MYSQL**



