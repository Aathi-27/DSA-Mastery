# Session 002

## Date
2026-07-12

## Pattern
Two Pointers

## Variant
Opposite Direction

---

## Problems Covered

- LC167 - Two Sum II
- LC11 - Container With Most Water
- LC42 - Trapping Rain Water (Conceptual)

---

## Objectives

- Build the Opposite Direction Two Pointer mental model.
- Understand search-space reduction.
- Learn elimination proofs.
- Understand why pointer movement is correct instead of memorizing it.

---

## Major Learnings

### Learning 1

Opposite Direction problems are not about moving pointers.

They are about shrinking the search space safely.

---

### Learning 2

Every pointer movement must permanently eliminate a set of impossible answers.

Never move a pointer without a proof.

---

### Learning 3

**Decision Rule**

Move the only pointer that has the potential to improve the answer.

---

### Learning 4

Stopping Rule and Loop Condition are different concepts.

**Loop Condition**

```
while(left < right)
```

**Stopping Rule**

Search space becomes empty or the required answer is found.

---

### Learning 5

Different problems eliminate different search spaces.

| Problem | Eliminated Unit |
|---|---|
| LC167 | Impossible pairs |
| LC11 | Impossible containers |
| LC42 | Bars whose trapped water has already been finalized |

---

## Biggest Insight

Pointer movement is the consequence.

Proof of elimination is the reason.

---

## Mentor Observations

**Strengths**

- Strong pattern recognition.
- Able to derive unseen reasoning.
- Good understanding of bottleneck concepts.

**Needs Improvement**

- Differentiate Loop Condition vs Decision Rule vs Stopping Rule.
- Describe elimination using search space instead of elements.

---

## Session Result

| Dimension | Rating |
|---|---|
| Recognition | ★★★★★ |
| Search Space | ★★★★★ |
| Invariant | ★★★★☆ |
| Decision Rule | ★★★★☆ |
| Proof | ★★★★☆ |
| Coding | ☆☆☆☆☆ |
