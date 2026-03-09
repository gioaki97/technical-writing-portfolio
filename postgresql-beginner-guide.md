### 1. PostgreSQL Beginner Guide
[Read the guide](postgresql-beginner-guide.md)

## Table of Contents

1. Introduction
2. Installing PostgreSQL
3. Creating Your First Database
4. Running a Basic Query
5. Common Beginner Mistakes
6. Conclusion

## Introduction

PostgreSQL is an open-source relational database system used to store and manage structured data. It is widely used in web applications, analytics systems, and enterprise software.

This guide introduces the basic concepts needed to start working with PostgreSQL.

---

## Installing PostgreSQL

PostgreSQL can be installed on Windows, macOS, and Linux.

After installation, the database server runs locally and can be accessed through a command-line interface or graphical tools.

---

## Creating Your First Database

Once PostgreSQL is installed, you can create a new database using a command like:

```sql
CREATE DATABASE my_first_database;
```

A database is a container that stores tables, data, and relationships.

---

## Running a Basic Query

Data in PostgreSQL is stored in tables.

A simple query looks like this:

```sql
SELECT * FROM users;
```

This command retrieves all records from the "users" table.

---

## Common Beginner Mistakes

Some common mistakes when starting with PostgreSQL include:

- Forgetting to connect to the correct database
- Confusing databases and tables
- Running queries without verifying table structure

---

## Conclusion

PostgreSQL is a powerful and flexible database system. Once you understand the basics of creating databases and running queries, you can begin designing more complex data structures.