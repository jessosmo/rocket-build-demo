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

## 2026-08-06 — 3D printing nose cone, centering rings, and motor mount tube

**Decision:** Modeled and 3D printed the nose cone, centering rings, and motor mount tube in Fusion 360. Body tube and fins will be sourced from other materials instead of printed.

**Reasoning:**
- Nose cone: modeled as a curved ogive profile (matching the OpenRocket design) with a 11.9mm peg to slide into the BT-50 tube.
- Centering rings: sized 19mm ID (fits over motor mount tube OD) / 23.8mm OD (fits inside body tube ID).
- Motor mount tube: sized 18mm ID (fits C6 motor) / 19mm OD.
- Body tube and fins kept as traditional materials rather than printed — printing them would add significant weight (denser than cardboard/balsa) and shift stability/altitude away from the simulated numbers.
- Nose cone kept as a solid model in Fusion; hollowing will be handled via low infill % in the slicer at print time rather than modeling it hollow directly.

**Open questions:**
- Need to confirm actual peg/tube fit once printed (measure and adjust tolerances if too tight/loose).
- Still need to add motor-delay decision entry (from earlier session) if not already logged.

## Template for future entries

```
## YYYY-MM-DD — [Short title]

**Decision:**

**Reasoning:**

**Open questions:**
```
