# 📝 Solved Examples

## Example 1

Question:

Retrieve Student Name and OrderID.

Answer:

SELECT Name, OrderID
FROM Students
INNER JOIN Orders
ON Students.ID = Orders.StudentID;

---

## Example 2

Question:

Retrieve all Students even if no Orders exist.

Answer:

SELECT *
FROM Students
LEFT JOIN Orders
ON Students.ID = Orders.StudentID;

---

## Example 3

Question:

Return all rows from Orders.

Answer:

RIGHT JOIN

---

## Example 4

Question:

Return every combination.

Answer:

CROSS JOIN