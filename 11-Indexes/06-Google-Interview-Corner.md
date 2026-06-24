# 🎯 Google Interview Corner

## Most Asked Concepts

### Why are Indexes needed?

Without Index:

Full Table Scan

Time Complexity:

O(N)

---

With Index:

Fast Search

Time Complexity:

O(log N)

---

### Clustered Index

Controls physical order of data.

Only one per table.

---

### Non-Clustered Index

Separate structure storing pointers.

Multiple allowed.

---

### Composite Index

Multiple columns combined.

Example:

(Name, Age)

---

### B-Tree Index

Most commonly used index.

Used by:

- MySQL
- PostgreSQL
- Oracle
- SQL Server

---

## Interview Tip

Always mention:

Indexes improve Read Performance

But may slow Insert, Update, Delete operations.