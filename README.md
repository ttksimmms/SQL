# SQL
# Project 1: Creating a database-School;

This project demonstrates SQL techniques for creating databases and designing a schema for managing school-related information by storing information related to students, teachers, and courses and facilitating data tracking. Included are sample SQL queries for tasks like inserting student information.

Creating database School

CREATE TABLE students(
student_id serial PRIMARY KEY,
first_name VARCHAR(50) NOT NULL,
last_name VARCHAR(50) NOT NULL,
homeroom_number integer,
phone VARCHAR(20) UNIQUE NOT NULL,
email VARCHAR(115) UNIQUE,
grad_year integer);

Inserting Student information

INSERT INTO
students(first_name,last_name,homeroom_number,phone,grad_year)VALUES
('Mark', 'Watney',5,'7755551234',2035);
