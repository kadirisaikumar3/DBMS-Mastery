# 🎯 Google Interview Corner

## Most Asked Concepts

### Storage Engine

Responsible for:

- Reading Data
- Writing Data
- Managing Pages

Examples:

- InnoDB
- MyISAM

---

### Buffer Pool

Caches frequently accessed pages.

Benefit:

Less Disk I/O

↓

Faster Queries

---

### Write-Ahead Logging (WAL)

Rule:

Write Log First

↓

Write Data Later

Benefit:

Crash Recovery

---

### MVCC

Multi-Version Concurrency Control

Allows:

Multiple Reads

Concurrent Writes

Minimal Blocking

---

### Query Optimizer

Chooses the cheapest execution plan.

Uses:

- Indexes
- Statistics
- Cost Estimation

---

## Interview Tip

Always explain the execution flow:

SQL Query

↓

Parser

↓

Optimizer

↓

Execution Engine

↓

Storage Engine

↓

Disk