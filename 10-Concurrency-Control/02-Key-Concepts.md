# 🔑 Key Concepts

## Lost Update

Two transactions update same data.

One update gets overwritten.

---

## Dirty Read

Transaction reads uncommitted data.

---

## Non-Repeatable Read

Same query returns different results.

---

## Phantom Read

New rows appear between repeated queries.

---

## Lock

Restricts access to data.

---

## Shared Lock (S)

Read Only

Multiple transactions allowed.

---

## Exclusive Lock (X)

Read + Write

Only one transaction allowed.

---

## Serializability

Concurrent execution behaves like serial execution.

---

## Two-Phase Locking (2PL)

Growing Phase

↓

Shrinking Phase