# ❌ Common Mistakes

## Mistake 1

Thinking SQL execution starts with data retrieval.

Actual flow:

Parser → Optimizer → Execution Engine.

---

## Mistake 2

Ignoring Execution Plans.

Always analyze EXPLAIN output for slow queries.

---

## Mistake 3

Confusing WAL with Backup.

WAL:

Crash Recovery

Backup:

Long-term Data Recovery

---

## Mistake 4

Believing Buffer Pool stores the entire database.

It stores only frequently accessed pages.

---

## Mistake 5

Ignoring database statistics.

Poor statistics can lead to inefficient query plans.