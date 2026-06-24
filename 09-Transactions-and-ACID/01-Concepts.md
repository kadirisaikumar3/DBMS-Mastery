# 📖 Transactions and ACID Concepts

## What is a Transaction?

A Transaction is a sequence of one or more database operations executed as a single unit.

Example:

Transfer ₹1000 from Account A to Account B

Steps:

1. Deduct ₹1000 from A
2. Add ₹1000 to B

Both operations must succeed together.

---

## Why Transactions?

Transactions ensure:

- Consistency
- Reliability
- Data Integrity

---

## Transaction Example

BEGIN TRANSACTION

Update Account A

Update Account B

COMMIT

---

## Transaction States

1. Active
2. Partially Committed
3. Committed
4. Failed
5. Aborted