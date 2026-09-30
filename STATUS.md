# Axial Flux QDD Actuator — Status

*Living board. Blanks mean unknown — fill as we decide.*
*Canonical home: https://github.com/RLH-Dynamics/rlh1_actuator*

## Goals
1. Hone EE design + FEA/simulation skills.
2. Open-source product: low-cost FOC driver for Robstride RS00- and RS02-sized actuators, plus a higher-performance axial-flux actuator.

## Current milestone
Project brain seeded on GitHub (README, STATUS, folder skeleton). Empty-repo blocker cleared. Claude preliminary design not yet imported.

## What's decided
| Area | Decision | Notes |
|------|----------|-------|
| Motor topology | — | axial flux is the product goal; confirm topology details |
| Stator / rotor layout | — | |
| Reduction (QDD) | — | |
| Sensing | — | |
| Controller / drive | FOC driver (goal) | target form-factor: Robstride RS00 / RS02 sized |
| Target torque / speed | — | |
| Voltage / bus | — | |
| Envelope / mass target | RS00 / RS02 class | compatibility with those actuator sizes |

## Open design choices
- Exact axial-flux topology and QDD reduction
- FOC driver scope vs actuator electromechanics (same repo or split?)
- Where Claude Code’s preliminary design artifacts live (to import)

## Known blockers
- Preliminary Claude design is reportedly disorganized and not in this repo

## Next 3 concrete steps
1. ~~Seed `rlh1_actuator` with README + STATUS + folder skeleton~~ — done 2026-09-30
2. Locate / import Claude’s preliminary design into a clear map (keep / revise / drop)
3. Stand up Notion front door linking to the repo

## Org
- **GitHub** (canonical): https://github.com/RLH-Dynamics/rlh1_actuator
- **Notion** (readable front door): https://app.notion.com/p/3eb753ce582a818abeacdc04d229f654
- **Claude Code**: primary design/intellectual work
- **Actuator Lab**: living status, decisions, coordination

## Questions for Chris
1. Where is Claude’s preliminary design today (local path, other repo, chat exports)?
2. ~~Seed the empty GitHub repo with README + STATUS + skeleton now?~~ — done with this seed
3. Target continuous/peak torque and speed (still open)?

---
*Last updated: 2026-09-30 — Notion front door linked. Prior: project-brain seed (empty repo → README, STATUS, folder skeleton).*
