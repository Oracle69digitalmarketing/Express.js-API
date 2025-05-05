# Express + PostgreSQL CRUD API

A simple RESTful API built with **Express.js** and **PostgreSQL** that supports full CRUD operations for a `users` table.

## Features
- GET all users
- GET a user by ID
- POST create a new user
- PUT update an existing user
- DELETE a user by ID

## Technologies
- Node.js
- Express.js
- PostgreSQL
- pg (PostgreSQL client)
- dotenv

## Database Setup
Run this SQL to create the required table:
```sql
CREATE TABLE users (
  id SERIAL PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100),
  age INTEGER
);
