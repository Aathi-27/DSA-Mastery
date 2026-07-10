# Pattern Dependency Map

> Which patterns must you know before learning the next one?

---

## Dependency Graph

```
[Arrays & Loops] (prerequisite for everything)
        │
        ├─── [Two Pointers]
        │         │
        │         └─── [Sliding Window]
        │                   │
        │                   └─── [Monotonic Stack]
        │
        ├─── [Binary Search] ─── [Binary Search on Answer]
        │
        ├─── [Recursion] ─── [Trees DFS/BFS]
        │                     │
        │                     └─── [Backtracking]
        │                     │
        │                     └─── [Dynamic Programming (1D)]
        │                                   │
        │                                   └─── [DP (2D/Knapsack)]
        │
        └─── [Graphs BFS/DFS] ─── [Union Find] ─── [Topological Sort]
```

---

## Blocked Patterns

Do NOT learn these until prerequisites are at 80%+:

| Pattern | Requires |
|---|---|
| Sliding Window | Two Pointers |
| Binary Search on Answer | Binary Search (classic) |
| Trees (DFS/BFS) | Recursion fundamentals |
| Backtracking | Trees DFS |
| DP (1D) | Recursion + Memoization |
| DP (2D) | DP (1D) |
| Graph Algorithms | BFS/DFS on Trees |
| Topological Sort | Graph BFS/DFS |
| Segment Tree | Binary Search + Arrays |

---

## Currently Unlocked

- [x] Two Pointers
- [x] Sliding Window
- [x] Monotonic Stack
- [x] Binary Search on Answer
- [ ] Trees (unlock after Phase 1 complete)
