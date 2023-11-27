## Database and Database Management System
We live in the age of Data; Whatever we do, see, hear, or even many things we are unaware of, is a form of data. To interact with, store, manage and use the information (data), we use tools called **Database (DB)**. So basically Database is any collection of related information that can be stored. _**Example**: to-do list (on a piece of paper or apps or whatever), Phone book, Amazon’s customers’ info including credit card, address, purchase history,..._ 

It is obvious that more complex (amount of data, the relation between them, and so on) and important information require advanced tools to secure and manage them. To do so, we use **Database Management Systems (DBMS)** which ironically are not an actual database, but a software program that helps users create and maintain a database to:

- Manage large amounts of information
- Handle Security and Backups
- Import and Export Data to interact with software applications

In fact, they are like a middle-man, between the database and the ones who want to use it. 
<img width="358" alt="Screenshot 2023-11-27 at 11 23 00" src="https://user-images.githubusercontent.com/56404983/285825745-1cc04ef4-32b4-4b78-865f-1364f5bb90b2.png">

> [!IMPORTANT]
> **CRUD**–stands for **Create**, **Read (Retrieve)**, **Update**, **Delete**–are the four main operations we do with DataBases. 
------------

## Data storage and Types of Databases 

The way data is stored defines the type of database. We have two general categories for forms of stored data:
- **Tables**
- **Anything but tables** :sweat_smile: No I'm not kidding!

Let's take a look at them:

|Tables|Anything BUT tables|
|---|---|
|Has rows and columns: <br/>    - Every **row** in a table stores one **record** <br/>   - Every **column** has some **attribute of that record**.|In forms of Key & Value, Documents (JSON, XML, etc), Graph|
|<img width="730" alt="Screenshot 2023-11-27 at 14 24 23" src="https://user-images.githubusercontent.com/56404983/285883519-0364a1a5-de8d-42ad-b65e-5c1966c68ee3.png">|<img width="717" alt="Screenshot 2023-11-27 at 14 28 56" src="https://user-images.githubusercontent.com/56404983/285880534-9a900b3a-0ac9-4942-a120-eba160a64f03.png"> <br/> <img width="341" alt="Screenshot 2023-11-27 at 14 23 52" src="https://user-images.githubusercontent.com/56404983/285887451-a2d24e59-94ad-4d75-b52a-c9f0577e6900.png">|

<br/>

Since we divided stored data into two categories, **for each of them we have a separate type of Database**. 

<br/>

|Relational Database (SQL)| Non-Relational Database (no-SQL)|
|---|---|
|Uses a ﻿﻿Relational Database Management Systems (**RDBMS**) to create/maintain a relational DB <br/> Example: _mySQL, Oracle, postgreSQL, mariaDB._|Uses Non-Relational Database Management Systems (**NRDBMS**) <br/> Example: _mongoDB, dynamoDB, apache cassandra, firebase._|
|﻿**SQL** (Structured Query Language) is the **standard language** for interacting with RDBMS to perform C.R.U.D operations|There is **no** standard language and each NRDBMS has their own langauge|

