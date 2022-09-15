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


***Mysql Database Containe**

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
 
**Create a Database**

```
CREATE DATABASE IF NOT EXISTS database_name;
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

