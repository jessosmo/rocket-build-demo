# Design Log

A running record of design decisions and the reasoning behind them. Update this whenever a spec changes — future-you (and anyone reviewing this repo) should be able to follow *why*, not just *what*.

---

## 2026-08-05 — Initial Design Spec

**Decision:** Chose Estes C6-5 as the target motor, BT-50 body tube, ogive nose cone, 3-fin configuration.

**Reasoning:**
- C6-5 is a common, well-documented beginner motor with a 5-second ejection delay suited to a first build.
- BT-50 is a standard Estes tube size with wide part availability, simplifying sourcing.
- Ogive nose cone chosen for a balance of aerodynamic efficiency and ease of modeling.
- 3 fins is the standard stable configuration for a first build.

**Open questions:**
- Fin size/shape (trapezoidal vs. elliptical) — not yet finalized.
- Centering ring count and spacing — depends on final motor mount tube length.
- Nose cone length — needs to be tuned against CG/CP once fins are set.

---

## Template for future entries

```
## YYYY-MM-DD — [Short title]

**Decision:**

**Reasoning:**

**Open questions:**
```
