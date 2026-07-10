# Pattern Name

> One-line summary of what this pattern solves.

---

## Recognition Triggers

Copy this list when reading a new problem. If ≥2 triggers fire, apply this pattern.

- [ ] Trigger 1
- [ ] Trigger 2
- [ ] Trigger 3

---

## Mental Model

> The analogy or physical intuition. What is this pattern *doing* in the real world?

---

## Framework (Skeleton Code)

```java
// Step 1: Initialize
// Step 2: Loop condition
// Step 3: Core logic
// Step 4: Return
```

---

## Decision Tree

```
Is the array sorted?
├── YES → Consider Two Pointers or Binary Search
└── NO  → Consider Sliding Window or Hashing

Is there a contiguous subarray constraint?
├── YES → Sliding Window
└── NO  → Two Pointers (if sorted)
```

---

## State Variables

| Variable | Type | Role | Initial Value |
|---|---|---|---|
| `left` | int | Left boundary | 0 |
| `right` | int | Right boundary | 0 |

---

## Dry Run Template

```
Input:
Expected Output:

Step | State | Action | Why
-----|-------|--------|----
  1  |       |        |
  2  |       |        |
```

---

## Interview Questions

1. What invariant does this pattern maintain?
2. Why does [pointer/window] move in this direction?
3. Can you solve this without extra space?
4. What is the time and space complexity?
5. How would this change if the array were unsorted?

---

## Brain Traps

- Trap 1: Describe the common wrong assumption.
- Trap 2:
- Trap 3:

---

## Common Mistakes

- Off-by-one in pointer initialization
- Forgetting to shrink window when constraint is violated
- Not handling edge cases (empty array, single element)

---

## My Personal Mistakes

<!-- Add mistakes here as you make them. Date every entry. -->

| Date | Problem | Mistake | Root Cause | Fix |
|---|---|---|---|---|
|  |  |  |  |  |

---

## Problems Covered

| LC # | Problem Name | Difficulty | Confidence | Last Revised |
|---|---|---|---|---|
|  |  |  |  |  |

---

## Revision Status

| Revision | Date | Score | Notes |
|---|---|---|---|
| 1st (Same Day) | | /10 | |
| 2nd (+1 Day) | | /10 | |
| 3rd (+3 Days) | | /10 | |
| 4th (+7 Days) | | /10 | |
| 5th (+14 Days) | | /10 | |
| 6th (+30 Days) | | /10 | |

---

## Mastery Percentage

**Current: 0%**

> Formula: (Problems solved without hints / Total pattern problems) × 100

---

## Future Problems

- [ ] LC —
- [ ] LC —
