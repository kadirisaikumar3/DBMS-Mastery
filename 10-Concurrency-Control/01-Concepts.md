# 📖 Concurrency Control Concepts

## What is Concurrency Control?

Concurrency Control ensures multiple transactions execute safely without affecting database consistency.

---

## Why Concurrency Control?

Without Concurrency Control:

- Data Corruption
- Inconsistent Results
- Lost Updates
- Dirty Reads

may occur.

---

## Concurrent Transactions

Multiple transactions executing at the same time.

Example:

T1: Withdraw ₹500

T2: Deposit ₹1000

Both access same account simultaneously.

---

## Goal

Maintain:

- Consistency
- Isolation
- Correctness