# Simulation Results



---

## Run 1 — [05/08/26]

**File:** `simulations/first-design.ork`

**Configuration:**
- Motor: C6-5
- Total mass: 43.7g
- Stability margin: 1.1 (calibers)

**Results:**
| Metric | Value |
|---|---|
| Apogee | 248m |
| Max velocity | 102 m/s |
| Max acceleration | 318 m/s^2 |
| Time to apogee | ~3.94 s |
| Ejection delay match | Motor delay is 5s vs. optimal 3.94s - ~1s overshoot, minor |

**Notes:**
- First simulated design. Stable at 1.1 cal. Delay mismatch is small; decided to stick with C6-5 rather than switch to c6-3.

---

## Template for future runs

```
## Run N — [date]

**File:** `simulations/[filename].ork`

**Configuration:**
- Motor:
- Total mass:
- Stability margin:

**Results:**
| Metric | Value |
|---|---|
| Apogee | |
| Max velocity | |
| Max acceleration | |
| Time to apogee | |
| Ejection delay match | |

**Notes:**
```
