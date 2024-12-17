The overall design of a database is called "Schema" of that database. 

There are 2 languages we use to interact with a database. 
***Data-Definition Language (DDL)*** : Any changes done to schema of the database, we use DDL.
***Data-Manipulation Language(DML)***: Any changes done to values in the database, we use DML. 

Basically, for any changes to design of the database, we use DDL and for values inside database, we use DML. 
 
There are 2 types of DML languages: 
1. Procedural DMLs( Imperative ): User specifies both data needed and how to get those data. 
2. Non-Procedural DMLs( Declarative ): User only specifies data needed. It will take care of how to get the data. EX: SQL


### 3 Levels of data abstraction
View level
Logical Level
Physical Level

### Database System structure. 
Functional components of a database:
1. Storage manager
2. Query processor components
The **Storage Manager** is responsible for **storing data** efficiently and managing the database files. It acts like an **interface** between the database and the physical storage (e.g., hard drives, SSDs).

The **Query Processor** is responsible for **interpreting** and **executing queries** sent to the database. It allows users to interact with the database system through **queries**, such as SQL commands.

When a user writes a query (e.g., `SELECT * FROM students WHERE age > 20;`), the query processor ensures that the query is processed efficiently and the correct results are returned.
[[001 Database System Architecture]] -> detailed information. 

### 2-Tier and 3-Tier Architecture
In 2 tier architecture, the frontend application will directly communicate with database through network. 
In 3 tier architecture, the frontend application will communicate only with backend server, which is connected to database. 