# Model Rocket Build Project

A documented model rocketry project — from design and simulation through build and flight testing. This repo tracks the process end-to-end as part of a longer-term goal of building an engineering portfolio.

## Project Overview

| | |
|---|---|
| **Motor** | Estes C6-5 |
| **Body tube** | BT-50 |
| **Nose cone** | Ogive |
| **Fins** | 3, trapezoidal/elliptical (TBD) |
| **Design tool** | [OpenRocket](https://openrocket.info/) |
| **Status** | 🟡 In design |

## Goals

- Design, simulate, and fly a stable rocket around the Estes C6-5 motor.
- Document design decisions (stability margin, materials, dimensions) with reasoning, not just results.
- Build a track record of hands-on engineering work — design iteration, simulation, testing, and analysis.

## Repo Structure

```
rocket-build-docs/
├── README.md                 ← you are here
├── docs/                      ← design specs & decision log
│   └── design-log.md
├── simulations/                ← OpenRocket .ork files, sim output, screenshots
│   └── simulation-results.md
├── build-log/                    ← dated build/construction entries
│   └── 2026-08-05-initial-design.md
└── images/                    ← renders, photos, stability diagrams
```

## Current Design Snapshot

- **Airframe:** BT-50 body tube, ogive nose cone, 3 fins
- **Motor mount:** 18mm inner tube sized for C6 motors, centering rings TBD
- **Stability target:** 1–2 caliber margin (CG ahead of CP)
- **Simulated performance:** TBD once first sim is run in OpenRocket

## Next Steps

- [ ] Finalize fin dimensions and centering ring spacing
- [ ] Run first OpenRocket stability/altitude simulation
- [ ] Log results in `simulations/simulation-results.md`
- [ ] Begin physical build and log progress in `build-log/`

## License

MIT (or update to your preference)
