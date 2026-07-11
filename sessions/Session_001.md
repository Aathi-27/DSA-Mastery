# Session 001

## Date
2026-07-11

## Pattern
Two Pointers

## Variant
Read & Write Pointer

---

## Problems Covered

- LC27 - Remove Element (Revision)
- LC283 - Move Zeroes (Conceptual Derivation)

---

## Objectives

- Shift from problem memorization to pattern recognition.
- Understand Read & Write Pointer deeply.
- Learn invariant-based thinking.
- Solve an unseen variation independently.

---

## Major Learnings

### Learning 1

Pointer movement is not index movement.

Pointer movement represents information gain.

---

### Learning 2

The algorithm never changes.

Only the definition of the valid element changes.

**Examples**

LC27
```
Valid = nums[i] != val
```

LC283
```
Valid = nums[i] != 0
```

Unseen Problem
```
Valid = nums[i] % 2 != 0
```

---

### Learning 3

**Read Pointer**

Scans every element.

**Write Pointer**

Always points to the next position where the next valid element should be placed.

---

### Learning 4

**Invariant**

Everything before the Write Pointer is already in its final correct position.

---

### Learning 5

**Decision Rule**

```
If current element is valid
  ↓
  Write
  ↓
  Advance Write
  ↓
  Advance Read
Else
  ↓
  Skip
  ↓
  Advance Read
```

---

## Unseen Problem

Move all odd numbers to the front.

**Status**

Solved completely through pattern derivation.

No memorized algorithm used.

---

## Mentor Observations

**Strengths**

- Strong example-based learning.
- Quickly derives new problems after understanding the pattern.
- Thinks aloud during dry runs.

**Needs Improvement**

- Think more in terms of invariants.
- Organize memory by recognition trigger instead of by problem.

---

## Session Result

| Dimension | Rating |
|---|---|
| Pattern Understanding | ★★★★★ |
| Dry Run | ★★★★★ |
| Recognition | ★★★★★ |
| Coding | ★★★★☆ |
| Invariant Thinking | ★★★☆☆ |
