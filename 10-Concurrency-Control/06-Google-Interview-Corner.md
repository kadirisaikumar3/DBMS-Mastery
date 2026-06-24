# 🎯 Google Interview Corner

## Most Asked Concepts

### Lost Update

Two transactions update the same data.

One update gets overwritten.

---

### Dirty Read

Reading data before transaction commits.

---

### Non-Repeatable Read

Same row returns different values.

---

### Phantom Read

New rows appear between queries.

---

### Shared Lock (S)

Allows:

Read

Read

---

### Exclusive Lock (X)

Allows:

Read

Write

Only one transaction at a time.

---

### Two-Phase Locking (2PL)

Guarantees Serializability.

Phases:

Growing Phase

↓

Shrinking Phase

---

## Interview Tip

Memorize:

Lost Update

Dirty Read

Non-Repeatable Read

Phantom Read

These are extremely common interview questions.