# Two Pointers

> Pattern file for all Two Pointer variants.

---

# Read & Write Pointer Variant

## Recognition Triggers

- In-place modification
- Preserve order
- O(1) extra space
- Remove or ignore elements
- Rearrange elements

---

## Mental Model

Read Pointer scans.

Write Pointer stores.

The Write Pointer always points to the next position where the next valid element should be placed.

---

## Core Question

What is a valid element?

---

## Invariant

Everything before the Write Pointer is already in its final correct position.

---

## Decision Rule

```
If valid
  ↓
  Write
  ↓
  Advance Write
  ↓
  Advance Read
Else
  ↓
  Advance Read
```

---

## Representative Problems

- LC27 — Remove Element
- LC283 — Move Zeroes
- LC26 — Remove Duplicates
- LC88 — Merge Sorted Array (partial)

---

## Biggest Insight

The algorithm remains the same.

Only the definition of the valid element changes.
