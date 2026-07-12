# DSA Mastery

> **External memory for DSA.** This repository replaces passive notes with a structured system for acquiring, retaining, retrieving, and applying algorithmic knowledge under interview pressure.

---

## Current Status — July 2026

| Metric | Value |
|---|---|
| Patterns Active | 4 |
| Problems Logged | 20 |
| Sessions Completed | 2 |
| Patterns Started | 2 |
| Patterns Mastered | 1 |
| Problems Added (Session 002) | 3 |
| Mental Models | 5 |
| New Invariants | 3 |
| Blind Retrieval Tests | 1 |
| Unseen Problems Solved | 1 |
| Recognition Triggers | 5 |
| Overall Mastery | ~40% |
| Next Revision Due | See [tracker/revision_tracker.md](tracker/revision_tracker.md) |

---

## Patterns Covered

| Pattern | Problems | Mastery |
|---|---|---|
| [Two Pointers](patterns/two_pointers.md) | LC27, LC283, LC977, LC167, LC11, LC15, LC42, LC16, LC75, LC88 | 55% |
| [Sliding Window](patterns/sliding_window.md) | LC209, LC3, LC567 | 50% |
| [Monotonic Stack](patterns/monotonic_stack.md) | LC496, LC739, LC901, LC84 | 40% |
| [Binary Search on Answer](patterns/binary_search_on_answer.md) | LC875, LC1011, LC1283 | 45% |
| [Trees](patterns/trees.md) | — | 0% |
| [Graphs](patterns/graphs.md) | — | 0% |
| [Heap](patterns/heap.md) | — | 0% |
| [Backtracking](patterns/backtracking.md) | — | 0% |
| [Greedy](patterns/greedy.md) | — | 0% |
| [Dynamic Programming](patterns/dynamic_programming.md) | — | 0% |

---

## Problems Solved

| # | Problem | Pattern | Difficulty | Confidence |
|---|---|---|---|---|
| [LC27](problems/LC27.md) | Remove Element | Two Pointers | Easy | 4/5 |
| [LC283](problems/LC283.md) | Move Zeroes | Two Pointers | Easy | 4/5 |
| [LC977](problems/LC977.md) | Squares of Sorted Array | Two Pointers | Easy | 4/5 |
| [LC167](problems/LC167.md) | Two Sum II | Two Pointers | Medium | 4/5 |
| [LC11](problems/LC11.md) | Container With Most Water | Two Pointers | Medium | 3/5 |
| [LC15](problems/LC15.md) | 3Sum | Two Pointers | Medium | 3/5 |
| [LC42](problems/LC42.md) | Trapping Rain Water | Two Pointers | Hard | 3/5 |
| [LC16](problems/LC16.md) | 3Sum Closest | Two Pointers | Medium | 3/5 |
| [LC75](problems/LC75.md) | Sort Colors | Two Pointers | Medium | 4/5 |
| [LC88](problems/LC88.md) | Merge Sorted Array | Two Pointers | Easy | 4/5 |
| [LC209](problems/LC209.md) | Minimum Size Subarray Sum | Sliding Window | Medium | 3/5 |
| [LC3](problems/LC3.md) | Longest Substring Without Repeating | Sliding Window | Medium | 3/5 |
| [LC567](problems/LC567.md) | Permutation in String | Sliding Window | Medium | 3/5 |
| [LC496](problems/LC496.md) | Next Greater Element I | Monotonic Stack | Easy | 3/5 |
| [LC739](problems/LC739.md) | Daily Temperatures | Monotonic Stack | Medium | 3/5 |
| [LC901](problems/LC901.md) | Online Stock Span | Monotonic Stack | Medium | 3/5 |
| [LC84](problems/LC84.md) | Largest Rectangle in Histogram | Monotonic Stack | Hard | 2/5 |
| [LC875](problems/LC875.md) | Koko Eating Bananas | Binary Search on Answer | Medium | 4/5 |
| [LC1011](problems/LC1011.md) | Ship Packages Within D Days | Binary Search on Answer | Medium | 4/5 |
| [LC1283](problems/LC1283.md) | Find Smallest Divisor | Binary Search on Answer | Medium | 3/5 |

---

## Learning Philosophy

**Acquire → Retain → Retrieve → Apply.**

Most DSA learners memorize solutions. This system builds *pattern recognition* — the ability to look at an unseen problem and identify which mental model applies, without hints.

Four rules govern everything:

1. **Pattern first.** Understand the pattern before touching code.
2. **Dry run before coding.** Trace through a small example manually.
3. **Never memorize code.** Reconstruct it from the algorithm every time.
4. **Record every personal mistake.** A mistake not recorded is a mistake repeated.

---

## Repository Structure

```
DSA-Mastery/
├── README.md                          ← This file (live dashboard)
├── DSA_Mastery_System_README.md       ← System rules and philosophy
│
├── roadmap/
│   ├── learning_roadmap.md            ← Ordered pattern progression
│   ├── placement_plan.md              ← Interview timeline
│   └── pattern_dependency_map.md
│
├── tracker/
│   ├── progress_dashboard.md          ← High-level summary
│   ├── mastery_tracker.md             ← Per-pattern mastery table
│   ├── revision_tracker.md            ← Scheduled revision checkpoints
│   └── interview_scores.md            ← Mock interview log
│
├── patterns/                          ← Deep-dive per pattern
├── problems/                          ← One file per LeetCode problem
├── sessions/                          ← Daily session logs
├── mental_models/                     ← Thinking frameworks
├── mistake_book/                      ← Recurring errors and debug patterns
├── interview_notes/                   ← Mock checklists and question bank
└── templates/                         ← Blank templates for new entries
```

---

## Quick Navigation

- **Start a new session** → [templates/session_template.md](templates/session_template.md)
- **Log a new problem** → [templates/problem_template.md](templates/problem_template.md)
- **Check what to revise** → [tracker/revision_tracker.md](tracker/revision_tracker.md)
- **Track overall progress** → [tracker/progress_dashboard.md](tracker/progress_dashboard.md)
- **Prepare for an interview** → [interview_notes/mock_interview_checklist.md](interview_notes/mock_interview_checklist.md)
- **Review a pattern** → [patterns/](patterns/README.md)
- **Review a problem** → [problems/](problems/README.md)

---

## How to Use This Repo Daily

### Before coding

1. Open [tracker/revision_tracker.md](tracker/revision_tracker.md) — complete any due revisions first.
2. Identify the pattern for today's problems.
3. Re-read the relevant pattern file.

### During a problem

1. Write the **Recognition Trigger** that told you which pattern to use.
2. Build the **Mental Model** — visualize state before writing code.
3. **Dry run** with a small example on paper.
4. Write the **Algorithm** in plain English.
5. **Then** write code.
6. Record your **Personal Mistakes** immediately after.

### After coding

1. Create or update the problem file under `problems/`.
2. Update the session log under `sessions/`.
3. Update revision dates in [tracker/revision_tracker.md](tracker/revision_tracker.md).
4. Update mastery % in [tracker/mastery_tracker.md](tracker/mastery_tracker.md).

---

## Revision Schedule

Every problem gets revisited at: **Same Day → +1 Day → +3 Days → +7 Days → +14 Days → +30 Days**

Revision means: *close all notes, read only the problem statement, solve from scratch.*

---

## Rules of the System

1. Pattern first — always identify the pattern before writing a single line of code.
2. Dry run before coding — trace the algorithm on a small example manually.
3. Never memorize code — reconstruct from the algorithm each time.
4. Record every personal mistake — in the problem file AND in [mistake_book/recurring_mistakes.md](mistake_book/recurring_mistakes.md).
5. Every session updates this repo — session log, revision dates, mastery tracker.
6. Revision is non-negotiable — due revisions before new problems.
7. Interview questions — extract at least one from every problem.
