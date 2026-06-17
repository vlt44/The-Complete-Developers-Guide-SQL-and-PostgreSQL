# SQL & PostgreSQL: The Complete Developer's Guide

A collection of exercises and projects completed while working through Stephen Grider's course, **[SQL and PostgreSQL: The Complete Developer's Guide](https://www.udemy.com/course/sql-and-postgresql/)**.

## Technologies Used

- PostgreSQL
- SQL
- pgAdmin
- Terminal

## Course Objectives

The course focuses on:

- Writing efficient queries to retrieve information
- Designing the schema, or structure, of the database
- Understanding when to use advanced features
- Managing the database in a production environment

## Database Design Process

The course introduces a simple framework for designing relational databases:

1. **Identify the entity**
   - What kind of thing are we storing?

2. **Define the attributes**
   - What properties does that thing have?

3. **Select appropriate data types**
   - What type of data should each property contain?

### What Tables Should We Make?

- Common features (like authentication, comments, etc) are frequently built with conventional table names and columns

- What type of resources exist in your app? Create a separate table for each of these features

- Features that seem to indicate a relationship or ownership between two types of resources need to be reflected in our table design

### Four Relationships

- Many-to-one
- One-to-many
- Many-to-many
- One-to-one

### Primary Key

Uniquely identifies record in a table

### Foreign Key

A foreign key creates a relationship between two tables by referencing the primary key of another table

## Project 1

[Simple - But Powerful - SQL Statements](/Project1/SQLstatements.sql)

## Project 2

[Photo Sharing DB](/Project2/)
