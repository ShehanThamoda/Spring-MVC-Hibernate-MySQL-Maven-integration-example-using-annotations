# Spring-MVC-Hibernate-MySQL-Maven-integration-example-using-annotations
Basic web project which is include add,edit,delete and view data using Spring MVC and Hibernate without using any xml files.

(1) Create the mysql database.
      CREATE TABLE EMPLOYEE(
        id INT NOT NULL auto_increment, 
        name VARCHAR(50) NOT NULL,
        joining_date DATE NOT NULL,
        salary DOUBLE NOT NULL,
        ssn VARCHAR(30) NOT NULL UNIQUE,
        PRIMARY KEY (id)
      );
    
      
(2) Create a web project with Maven.Then divide the packages like as follows. 
     configuration (Hibernate and Spring configure in here using java class with annotations).
     Controller
     Service
     Dao
     Model
     
