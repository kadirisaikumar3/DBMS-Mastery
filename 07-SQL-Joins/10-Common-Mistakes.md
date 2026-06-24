# ❌ Common Mistakes

## Mistake 1

Forgetting JOIN Condition.

Always use:

ON Table1.ID = Table2.ID

---

## Mistake 2

Using CROSS JOIN accidentally.

May produce huge result sets.

---

## Mistake 3

Confusing LEFT and RIGHT JOIN.

Remember:

LEFT = Keep Left Table

RIGHT = Keep Right Table

---

## Mistake 4

Ignoring NULL values in Joins.

LEFT and RIGHT JOIN often return NULLs.