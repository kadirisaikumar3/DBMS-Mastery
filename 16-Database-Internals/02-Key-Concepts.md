# 🔑 Key Concepts

## Storage Engine

Responsible for storing and retrieving data.

Examples:

- InnoDB
- MyISAM

---

## Pages

Databases store records in fixed-size pages.

Typical size:

16 KB

---

## Buffer Pool

Stores frequently accessed pages in memory.

Reduces disk I/O.

---

## Write-Ahead Logging (WAL)

Logs changes before writing data to disk.

Improves crash recovery.

---

## MVCC

Multi-Version Concurrency Control.

Allows multiple transactions to access data simultaneously without blocking each other.

---

## Query Optimizer

Chooses the most efficient execution plan.

---

## Execution Plan

Sequence of operations used to execute a SQL query.