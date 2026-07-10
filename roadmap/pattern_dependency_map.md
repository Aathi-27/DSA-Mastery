# Pattern Dependency Map

> Learn patterns in dependency order. A pattern with prerequisites should only be started after its dependencies are at 60%+ mastery.

---

## Dependency Graph

```
Arrays / Basic Loops
         │
    ┌────┴─────────┐
    │               │
Two Pointers    Sliding Window
    │               │
    └────┬────────┘
         │
  ┌────┴────────┐
  │               │
Monotonic     Binary Search
  Stack         on Answer
  │               │
  └────┬────────┘
         │
  ┌────┴────┐
  │           │
Trees        Heap
  │           │
  └──┬─────┘
      │
   Graphs
      │
  ┌──┴────┐
  │           │
Greedy    Dynamic Programming
                │
           Backtracking
```

---

## Prerequisite Table

| Pattern | Requires | Notes |
|---|---|---|
| Two Pointers | Array basics | Entry point |
| Sliding Window | Array basics | Entry point |
| Monotonic Stack | Two Pointers | Stack intuition builds on pointer movement |
| Binary Search on Answer | Binary Search basics | Must understand classic binary search first |
| Trees | Recursion, DFS/BFS concept | New data structure |
| Heap | Trees (binary heap is a tree) | |
| Graphs | Trees, BFS/DFS | Extension of tree traversal |
| Greedy | Arrays, Sorting | Proof-by-exchange intuition |
| Dynamic Programming | Recursion, Memoization | Hardest — enter last |
| Backtracking | Recursion, Trees | State-space search |

---

## When to Move to the Next Pattern

Move forward when, for the current pattern:
- You can identify the pattern in an unseen problem within 60 seconds.
- You can write the framework skeleton without reference.
- mastery_tracker.md shows ≥60%.
- You have solved at least 3 problems cold.
