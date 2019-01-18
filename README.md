# JDBC_Assignment1
Uppgift med SQL-kod och JAVA-kod

SQL-code:

CREATE DATABASE sqlandjava;

CREATE SCHEMA `sqljava`;

CREATE TABLE `sqljava`.`people_sqlandjava`(
`person_id`INT NOT NULL,
`firstname`VARCHAR(45)NOT NULL,
`lastname`VARCHAR(45)NOT NULL,
PRIMARY KEY(`person_id`));

INSERT INTO `sqljava`.`people_sqlandjava`(`person_id`,`firstname`,`lastname`)VALUES('1','Anna','Bolt');
INSERT INTO `sqljava`.`people_sqlandjava`(`person_id`,`firstname`,`lastname`)VALUES();
INSERT INTO `sqljava`.`people_sqlandjava`(`person_id`,`firstname`,`lastname`)VALUES();
INSERT INTO `sqljava`.`people_sqlandjava`(`person_id`,`firstname`,`lastname`)VALUES();
