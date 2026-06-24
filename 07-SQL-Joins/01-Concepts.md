# 📖 SQL Joins

## What is a Join?

A Join combines rows from two or more tables based on a related column.

---

## Why Use Joins?

To retrieve related information stored across multiple tables.

Example:

Student Table

Order Table

Retrieve:

Student Name + Order Details

---

## Types of Joins

1. INNER JOIN
2. LEFT JOIN
3. RIGHT JOIN
4. FULL OUTER JOIN
5. SELF JOIN
6. CROSS JOIN

---

## Example

Students

| ID | Name |
|----|------|
| 1 | Sai |
| 2 | John |

Orders

| OrderID | StudentID |
|----------|-----------|
| 101 | 1 |

Join Result:

Sai → Order 101