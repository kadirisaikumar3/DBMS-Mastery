# ❌ Common Mistakes

## Mistake 1

Confusing Fragmentation with Replication.

Fragmentation:

Splits Data.

Replication:

Copies Data.

---

## Mistake 2

Assuming Replication guarantees consistency.

Replication improves availability but consistency depends on the replication strategy.

---

## Mistake 3

Ignoring network partitions.

Distributed systems must handle network failures gracefully.

---

## Mistake 4

Believing 2PC never blocks.

If the coordinator fails, participants may remain blocked.

---

## Mistake 5

Using synchronous replication everywhere.

It may increase latency significantly.