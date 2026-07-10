# Learning Roadmap

> Ordered pattern progression from fundamentals to advanced. Each tier must be solid before moving to the next.

---

## Tier 1 — Foundation (Weeks 1–3)

These patterns share a common DNA: maintain two indices that converge toward an answer. Master these first because every subsequent pattern builds on linear traversal discipline.

| Pattern | Goal | Entry Problem |
|---|---|---|
| Two Pointers | Reduce O(n²) to O(n) on sorted arrays | LC27 (Remove Element) |
| Sliding Window | Optimize subarray/substring queries | LC209 (Min Size Subarray Sum) |

**Exit criteria for Tier 1:**
- Solve any Two Pointers or Sliding Window problem cold (no hints) in under 20 minutes.
- Explain the invariant maintained by each pattern without notes.

---

## Tier 2 — Stack-Based Patterns (Weeks 4–5)

Monotonic Stack requires understanding *when* to pop — which is a logical leap from Tier 1. Binary Search on Answer requires abstracting a concrete problem into a feasibility function.

| Pattern | Goal | Entry Problem |
|---|---|---|
| Monotonic Stack | Solve next/previous greater/smaller in O(n) | LC496 (Next Greater Element I) |
| Binary Search on Answer | Reduce optimization to binary search on a value space | LC875 (Koko Eating Bananas) |

**Exit criteria for Tier 2:**
- Design the helper/feasibility function for a new Binary Search on Answer problem without reference.
- Implement Monotonic Stack without confusion about push/pop order.

---

## Tier 3 — Tree Patterns (Weeks 6–8)

| Pattern | Core Concepts |
|---|---|
| Binary Tree Traversal | DFS (inorder, preorder, postorder), BFS (level order) |
| Binary Search Tree | Search, Insert, Delete, Validate |
| Tree DP | Bottom-up aggregation, diameter, max path sum |

**Entry problems:** LC104, LC226, LC543, LC110, LC124

---

## Tier 4 — Graph Patterns (Weeks 9–11)

| Pattern | Core Concepts |
|---|---|
| BFS/DFS on Grid | Islands, connected components, flood fill |
| Topological Sort | Dependency ordering (Kahn’s + DFS) |
| Union-Find | Dynamic connectivity, cycle detection |
| Shortest Path | Dijkstra, BFS for unweighted |

**Entry problems:** LC200, LC695, LC417, LC207, LC684

---

## Tier 5 — Heap & Greedy (Weeks 12–13)

| Pattern | Core Concepts |
|---|---|
| Heap / Priority Queue | Top-K, merge K sorted, median stream |
| Greedy | Local optimal → global optimal, interval scheduling |

**Entry problems:** LC215, LC347, LC295, LC435, LC452

---

## Tier 6 — Dynamic Programming (Weeks 14–17)

DP is a destination, not a starting point. All previous patterns should be solid before entering this tier.

| Sub-pattern | Entry Problem |
|---|---|
| 1D DP (Fibonacci family) | LC70, LC198 |
| 2D DP (Grid paths) | LC62, LC64 |
| Subsequences | LC300, LC1143 |
| Knapsack | LC416, LC518 |
| Interval DP | LC516, LC1312 |

---

## Tier 7 — Backtracking (Weeks 18–19)

| Sub-pattern | Entry Problem |
|---|---|
| Subsets | LC78 |
| Permutations | LC46 |
| Combinations | LC77, LC39 |
| Constraint satisfaction | LC51 (N-Queens) |

---

## Current Position

**Active:** Tier 1 + Tier 2 (all four patterns covered, consolidation phase)

**Next:** Enter Tier 3 (Trees) after mastery_tracker shows ≥70% on all Tier 1/2 patterns.
