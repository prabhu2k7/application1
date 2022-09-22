# application1


Please create database and use query/modify according to your needs. 

Model bean:
private long id;
private String firstName;
private String lastName;
private String emailId;
	
	

Queries:
-------------
CREATE DATABASE TRAINING_APP; 
CREATE TABLE training_app.users
(
id int NOT NULL AUTO_INCREMENT,
first_name varchar(255),
last_name varchar(255),
email_address varchar(255),
 PRIMARY KEY (id)
);

DROP TABLE TRAINING_APP.users;

INSERT INTO TRAINING_APP.users (id,first_name, last_name, email_address)
VALUES ('1','Raj', 'kumar', 'raj@gmail.com');


select * from  training_app.users;
