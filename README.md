# SQL_interview_questions
## Popular Database Interview Questions And Answers
#### 1) What do you understand by ‘Database’? 
         Answer: Database is an organized collection of related data where the data is stored and organized to serve some specific purpose.
         For Example, A librarian maintain a database of all the information related to the books that are available in the library.
##### 2) What do you understand by Data Redundancy?       
         Answer: Duplication of data in the database is known as data redundancy. As a result of data redundancy, duplicated data is present at multiple locations,    hence it leads to wastage of the storage space and the integrity of the database is destroyed.
#### 3) What are the various types of relationships in Database? Define them.         
          Answer: There are 3 types of relationships in Database:

          One-to-one: One table has a relationship with another table having the similar kind of column. Each primary key relates to only one or no record in the related table.
          One-to-many: One table has a relationship with another table that has primary and foreign key relations. The primary key table contains only one record that relates to none, one or many records in the related table.
          Many-to-many: Each record in both the tables can relate to many numbers of records in another table.

#### 4) What are the different types of Normalization?
          Answer: Different types of Normalization are:

          First Normal Form (1NF): A relation is said to be in 1NF only when all the entities of the table contain unique or atomic values.
          Second Normal Form (2NF): A relation is said to be in 2NF only if it is in 1NF and all the non-key attribute of the table is fully dependent on the primary key.
          Third Normal Form (3NF): A relation is said to be in 3NF only if it is in 2NF and every non-key attribute of the table is not transitively dependent on the primary key.
#### 5) What is SQL?

        Answer: Structured Query language, SQL is an ANSI(American National Standard Institute) standard programming language that is designed specifically for storing and managing the data in the relational database management system (RDBMS) using all kinds of data operations.          
#### 6) How many SQL statements are used? Define them.

        Answer: SQL statements are basically divided into three categories, DDL, DML, and DCL.
        They can be defined as:

        Data Definition Language (DDL): commands are used to define the structure that holds the data. These commands are auto-committed i.e. changes done by the DDL commands on the database are saved permanently.
        Data Manipulation Language (DML): commands are used to manipulate the data of the database. These commands are not auto-committed and can be rolled back.
        Data Control Language (DCL): commands are used to control the visibility of the data in the database like revoke access permission for using data in the database.       
        
#### 7) Enlist some commands of DDL, DML, and DCL.

        Answer: Data Definition Language (DDL) commands:

        CREATE to create a new table or database.
        ALTER for alteration.
        TRUNCATE to delete data from the table.
        DROP to drop a table.
        RENAME to rename a table.
        Data Manipulation Language (DML) commands:

        INSERT to insert a new row.
        UPDATE to update an existing row.
        DELETE to delete a row.
        MERGE for merging two rows or two tables.
        Data Control Language (DCL) commands:

        COMMIT to permanently save.
        ROLLBACK to undo the change.
        SAVEPOINT to save temporarily.      
        
#### 8) Define DML Compiler.

         Answer: DML compiler translates DML statements in a query language into a low-level instruction and the generated instruction can be understood by Query Evaluation Engine.

#### 9) What is DDL interpreter?

          Answer: DDL Interpreter interprets the DDL statements and records the generated statements in the table containing metadata.     
          
#### 10) What do you understand by Functional dependency?

          Answer: A relation is said to be in functional dependency when one attribute uniquely defines another attribute.

          For Example, R is a Relation, X and Y are two attributes. T1 and T2 are two tuples. Then,

          T1[X]=T2[X] and T1[Y]=T2[Y]

          Means, the value of component X uniquely define the value of component Y.

          Also, X->Y means Y is functionally dependent on X.     

 #### 11) What do you understand by the E-R model?

          Answer: E-R model is an Entity-Relationship model which defines the conceptual view of the database.

          The E-R model basically shows the real-world entities and their association/relations. Entities here represent the set of attributes in the database.
  #### 12) Define Cursor and its types.

          Answer: Cursor is a temporary work area that stores the data, as well as the result set, occurred after manipulation of data retrieved. A cursor can hold only one row at a time.

          The 2 types of Cursor are:

          Implicit cursors are declared automatically when DML statements like INSERT, UPDATE, DELETE is executed.
          Explicit cursors have to be declared when SELECT statements that are returning more than one row are executed     
       
#### 13) What is the Database transaction?

          Answer: Sequence of operation performed which changes the consistent state of the database to another is known as the database transaction. After the completion of the transaction, either the successful completion is reflected in the system or the transaction fails and no change is reflected. 
       
#### 14) What do you understand by Join?

          Answer: Join is the process of deriving the relationship between different tables by combining columns from one or more tables having common values in each. When a table joins with itself, it is known as Self Join.    
#### 15) Differentiate between ‘Cluster’ and ‘Non-cluster’ index.

          Answer: Clustered index alters the table and re-order the way in which the records are stored in the table. Data retrieval is made faster by using the clustered index.

          A Non-clustered index does alter the records that are stored in the table but creates a completely different object within the table.       
       
       
       
       
