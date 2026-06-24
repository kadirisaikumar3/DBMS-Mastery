# 🎯 Google Interview Corner

## Most Asked SQL Queries

### SELECT

Retrieve data.

SELECT * FROM Students;

---

### WHERE

Filter data.

SELECT *
FROM Students
WHERE Age > 20;

---

### ORDER BY

Sort records.

SELECT *
FROM Students
ORDER BY Age DESC;

---

### GROUP BY

Group records.

SELECT Department,
COUNT(*)
FROM Employees
GROUP BY Department;

---

### HAVING

Filter grouped records.

SELECT Department,
COUNT(*)
FROM Employees
GROUP BY Department
HAVING COUNT(*) > 5;

---

## Interview Tip

Remember SQL Execution Order:

FROM
↓
WHERE
↓
GROUP BY
↓
HAVING
↓
SELECT
↓
ORDER BY
↓
LIMIT