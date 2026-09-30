# rlh1_actuator

Canonical project brain for this open-source actuator effort. Technical specs are TBD.

## Product goals

1. A general-purpose, low-cost FOC driver for Robstride RS00- and RS02-sized actuators.
2. A novel higher-performance axial-flux quasi-direct-drive (QDD) actuator.

A parallel aim is to hone electrical-engineering design and FEA/simulation skills.

## Status

Living status, open questions, and next steps: [STATUS.md](STATUS.md).

## Folder map

| Path | What belongs here |
|------|-------------------|
| `docs/` | Architecture and design notes |
| `docs/decisions/` | ADRs / decision log |
| `hardware/` | Actuator, mechanical, and electromagnetics notes (CAD lives elsewhere for now) |
| `firmware/` | FOC driver firmware |
| `electronics/` | Schematics and PCB notes |
| `simulation/` | FEA, motor, and control simulations |
| `tools/` | Scripts and helpers |

GitHub is the canonical home. Notion front door: https://app.notion.com/p/3eb753ce582a818abeacdc04d229f654
