# Mistake Book

> Every mistake recorded here is a mistake that will not repeat.

---

## Session 001

### Mistake

Assumed Write Pointer moves whenever Read Pointer moves.

**Correction**

Write Pointer moves only after successfully placing a valid element.

**Status:** Resolved

---

### Mistake

Thought invariant meant: "Elements before Write are checked."

**Correction**

Invariant means: "Elements before Write are already finalized and will never change."

**Status:** Resolved

---

## Session 002

### Mistake

Confused Loop Condition with Decision Rule.

**Correction**

Loop Condition controls iteration.

Decision Rule chooses which pointer moves.

**Status:** Resolved

---

### Mistake

Described elimination in terms of elements.

**Correction**

Always describe elimination in terms of search space.

**Status:** Improving
