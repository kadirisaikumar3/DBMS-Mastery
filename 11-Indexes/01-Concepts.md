# 📖 Index Concepts

## What is an Index?

An Index is a data structure that improves the speed of data retrieval.

Think of it like an index in a book.

Instead of reading every page, you directly jump to the required page.

---

## Why Use Indexes?

Without Index:

Database performs Full Table Scan.

With Index:

Database directly locates required records.

---

## Example

Student Table

| ID | Name |
|----|------|
| 1 | Sai |
| 2 | John |

Searching:

WHERE ID = 2

Index helps find the record quickly.

---

## Goal

Reduce query execution time.