# Tsinderhoz Proposal

**Federated Autonomous Resilience Infrastructure**  
System architect: **Vadym Tsinderhoz**  
Architecture baseline: **TP-2026-RD-001, version 1.0**

## Current repository status

This repository currently holds an architecture description and a proposed software contract. **The reference application is not present in this repository.** It cannot currently be installed, built or run.

A repository check on **3 November 2026** found only `README.md` and `LICENSE` before this documentation correction. Both available historical commits were inspected; neither contained the application. The only branch was `main`. No software recovery from that history is possible.

The earlier README described an executable implementation, 42 passing tests, registries, an API, a CLI, Docker and CI. The corresponding files were absent. Those statements are now recorded as **unimplemented requirements**, rather than claimed results, in [the implementation plan](docs/IMPLEMENTATION_PLAN.md).

## Architecture

The proposal describes civilian infrastructure for continuity of essential services: energy, water, shelter support, repair, logistics, communications and accountable human decisions. Domain controllers retain local safety limits and operators retain authority. Planning and AI are advisory; a future software prototype would not establish the safety or certification of physical equipment.

The controlled architecture document is `TSINDERHOZ_PROPOSAL_v1.0_EN.pdf` (TP-2026-RD-001). It is maintained separately and is **not bundled here**. A design document is not a substitute for source code or executed test evidence.

## What is available

| Item | Status |
| --- | --- |
| Architecture overview | This README |
| Proposed software features and example contracts | [Implementation plan](docs/IMPLEMENTATION_PLAN.md); not implemented |
| Evidence and recovery checklist | [Repository status](docs/REPOSITORY_STATUS.md) |
| Runtime source, configuration and registries | Missing |
| Tests, CI, Docker, API and CLI | Missing / not executed |
| Installers and software releases | None |

There are no runnable installation commands or CI badges until their corresponding files exist and have been verified.

## Recovery and implementation sequence

1. Locate an authentic source archive or other verified copy. Preserve its provenance and compare it with the architecture document.
2. If no source copy exists, implement a new, explicitly versioned prototype from the architecture; do not label it recovered software.
3. Add a reproducible package, configuration, input contracts and tests for actual behavior.
4. Test state persistence, replay rejection, safe rejection of invalid commands and deterministic calculations before publishing implementation claims.
5. Add platform builds and named releases tied to exact commits and test evidence.

## License and attribution

The current [LICENSE](LICENSE) contains **Apache License 2.0**. Earlier README language describing a proprietary license did not match that file. This documentation correction does not replace the license or rewrite its history.

Architecture authorship: **Vadym Tsinderhoz**. Any future licensing decision should be recorded explicitly and consistently with the files to which it applies.
