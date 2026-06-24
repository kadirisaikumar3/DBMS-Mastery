# 📖 Stored Procedures Concepts

## What is a Stored Procedure?

A Stored Procedure is a collection of SQL statements stored in the database.

It can be executed whenever needed.

---

## Why Use Stored Procedures?

Benefits:

- Reusability
- Better Performance
- Security
- Reduced Network Traffic
- Easier Maintenance

---

## Example

CREATE PROCEDURE GetStudents
AS
SELECT * FROM Students;

---

## Execution

EXEC GetStudents;

---

## Goal

Store business logic inside the database.