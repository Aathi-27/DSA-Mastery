# [Pattern Name]

---

## Recognition Triggers

Use this pattern when the problem has:
- Trigger 1
- Trigger 2
- Trigger 3

---

## Mental Model

> One paragraph: what is the pattern doing physically? Describe it as a spatial or mechanical process.

---

## Framework

```
Initialize state

while (termination condition):
    expand / move / decide
    update state
    update answer

return answer
```

---

## Decision Tree

```
Is the array sorted?
    Yes → Two Pointers likely
Is the problem about contiguous subarrays?
    Yes → Sliding Window likely
Is the answer a value in a range, and feasibility checkable?
    Yes → Binary Search on Answer
Is the problem next/previous greater/smaller?
    Yes → Monotonic Stack
```

---

## State Variables

| Variable | Role |
|---|---|
| left | Left boundary |
| right | Right boundary |
| answer | Running best |

---

## Dry Run Template

```
Input: []
Initial state: left=, right=, answer=

Iteration 1: ...
Iteration 2: ...

Final: answer=
```

---

## Interview Questions

1. ?
2. ?
3. ?

---

## Brain Traps

- Trap 1: ...
- Trap 2: ...

---

## Common Mistakes

- Mistake 1
- Mistake 2

---

## My Personal Mistakes

- [ ] Add after first problems

---

## Problems Covered

| # | Problem | Difficulty | Confidence |
|---|---|---|---|
| | | | |

---

## Revision Status

| Checkpoint | Done? |
|---|---|
| Learned | ❌ |
| +1 Day | ❌ |
| +7 Days | ❌ |
| +14 Days | ❌ |

---

## Mastery Percentage

**Current: 0%**

---

## Future Problems

- Problem A
- Problem B
