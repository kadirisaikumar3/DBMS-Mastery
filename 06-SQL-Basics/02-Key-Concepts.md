# 🔑 Key Concepts

## SELECT

Retrieves data.

Example:

SELECT * FROM Student;

---

## WHERE

Filters records.

Example:

SELECT * FROM Student
WHERE Age > 20;

---

## ORDER BY

Sorts records.

Example:

SELECT * FROM Student
ORDER BY Age;

---

## DISTINCT

Removes duplicates.

Example:

SELECT DISTINCT City
FROM Student;

---

## LIMIT

Restricts rows.

Example:

SELECT * FROM Student
LIMIT 5;

---

## GROUP BY

Groups similar records.

Example:

SELECT Department,
COUNT(*)
FROM Employee
GROUP BY Department;

---

## HAVING

Filters grouped data.

Example:

SELECT Department,
COUNT(*)
FROM Employee
GROUP BY Department
HAVING COUNT(*) > 5;