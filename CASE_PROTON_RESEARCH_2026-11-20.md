# Public-source security research | Proton-related client software
**Offline engineering analysis and synthetic regression methodology**

![Python](https://img.shields.io/badge/Analysis-Python%20oracles-3776AB?logo=python&logoColor=white) ![Node](https://img.shields.io/badge/Review-JavaScript%20%2F%20Node.js-339933?logo=nodedotjs&logoColor=white) ![Git](https://img.shields.io/badge/Method-Source--pinned%20Git-F05032?logo=git&logoColor=white) ![Scope](https://img.shields.io/badge/Scope-Offline%20research-334155)

**Research context:** review of publicly available Proton-related web client / SDK source and development of **first-party, local synthetic regression checks** for permission and state-handling assumptions.

## What the work demonstrates

- Inspecting public upstream repositories and identifying **exact source revisions** before analysis.
- Building controlled, offline fixtures that compare declared versus observed data and permission states.
- Using deterministic oracles and provenance/evidence records to avoid mistaking a synthetic discrepancy for a real vendor vulnerability.
- Separating source-code reading, local model-level tests and actual deployed-system behavior.

**Research status:** No confirmed Proton vulnerability, production-system penetration test, disclosure submission, bounty award, customer endorsement or vendor engagement is claimed. A local negative case or synthetic permission refusal does **not** prove a defect in Proton servers or encryption. Work is privately retained pending technical, licensing and coordinated-disclosure review.

**IP and conduct:** no upstream source is copied here; no exploit path, unverified security finding, private research log, customer data or third-party branding is distributed. Proton is named only to identify the public-source research context. **Razorglint Labs is independent and not affiliated with, sponsored by or endorsed by Proton.**

[Engineering portfolio](README.md) · [BRE method case](CASE_BRE_2026-11-20.md) · [Elite Pantry](CASE_ELITE_PANTRY_2026-11-20.md)

*Research method only · 20 November 2026 · No security assurance, permission to test production or vulnerability disclosure implied.*
