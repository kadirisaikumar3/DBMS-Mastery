# 📖 Views and Triggers Concepts

## What is a View?

A View is a virtual table based on a SQL query.

A View does not store data itself.

It displays data from one or more tables.

---

## Example

CREATE VIEW StudentView AS
SELECT ID, Name
FROM Students;

---

## Why Use Views?

- Security
- Simplicity
- Data Abstraction
- Reusability

---

## What is a Trigger?

A Trigger is a database object that automatically executes when an event occurs.

Events:

- INSERT
- UPDATE
- DELETE

---

## Example

When a new employee is added:

Automatically create an audit record.