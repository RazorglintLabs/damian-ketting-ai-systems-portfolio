# Systems Index — Public Summary

This index summarizes finished systems from the supplied handbooks. It is intended as a recruiter-safe map, not a full evidence dump.

| # | System | Category | Public-Safe Core | Proof State | Recruiter Signal |
|---:|---|---|---|---|---|
| 1 | SAR | Agent governance | Ed25519-signed policy + receipt chain + fail-closed guardian | 243 tests | governed AI/agent workflow thinking |
| 2 | FleetSim | Execution governance | Trust-plane simulation with severity ladder + RTH pre-auth | 103 tests | safety, gates, runtime controls |
| 3 | EU AI Act Readiness | Policy/compliance readiness | Read-only evidence compiler + adapter architecture | 66 tests, 33 boundary checks | compliance evidence automation |
| 4 | IronSeal | Execution governance | Deny-by-default cages + monotonic budgets + domain-separated Merkle | 8 test files | safety, gates, runtime controls |
| 5 | VerdictGate | Decision/verdict engine | Policy evaluation + crypto + SDK-style access patterns | 8/8 Rust tests | decision logic and verdict modeling |
| 6 | ProofChain | Audit ledger | Incremental Merkle accumulator + server/client proof pattern | 20/20 Rust tests | tamper-evident evidence systems |
| 7 | SealVault | Evidence sealing | Hash-only transmission + five-question seal pattern | 23/23 Rust tests | cryptographic proof workflows |
| 8 | Blackiron | Cryptographic substrate | SHA-256 chains + domain-separated Merkle + HLC + receipts | Integration tests pass | low-level proof infrastructure |
| 9 | Voidlock | Execution governance | Zero-trust void cages + capability attenuation + stateless judge | 6 test files | safety, gates, runtime controls |
| 10 | PolicySourceEngine | Policy/compliance readiness | Deterministic policy pack loader + checklist evaluator | 4 test files | compliance evidence automation |
| 11 | TrustContinuityMapper | Drift/trust continuity | Trust timeline reconstruction + segment classification | Demo + verify | trust and drift analysis |
| 12 | DecisionProvenanceTracker | Decision/verdict engine | Decision lineage graph with hash-verified edges | Demo + verify | decision logic and verdict modeling |
| 13 | ComplianceDriftDetector | Drift/trust continuity | Policy-behavior alignment engine + trend detection | 27 tests, all PASS | trust and drift analysis |
| 14 | ReasonForge | Data quality / ML pipeline | Schema validation + dedup + leakage detection + Pass@1 | 93 tests, all PASS | LLM data quality and eval tooling |
| 15 | Isengard | Automation gateway | n8n + FastAPI gateway + deny-by-default + kill switch | Policy + audit + smoke tests | safe automation orchestration |
| 16 | SAR_LIFEBOAT | Archive/lifeboat | SHA-256 verified evidence archive outside production | Hash verification | evidence preservation |
| 17 | BountyPipeline | Supply-chain/security research | Signal triage + evidence packing + claim safety | 315 tests, all PASS | security research workflow |
| 18 | Developer Supply-Chain Proof Kit | Supply-chain/security research | Read-only local exposure scanner + receipt chain | Sample project verification | security research workflow |
| 19 | Command Guardian | Execution governance | Gate 0 + 4-gate terminal enforcement + sanitized DENY receipts | 131 tests, all PASS | safety, gates, runtime controls |
| 20 | OpenClaw | Agent governance | Governed agent stack with deny-by-default + receipt pipeline | Field-reconciled | governed AI/agent workflow thinking |
| 21 | Razorglint Painpoint Solver | Buyer-facing product candidate | Pain-to-system-to-proof navigation | Documentation-only | commercial product mapping |
| 22 | Rust_Modules | Cryptographic/data substrate | Sovereign Rust crates for cache, ledger, vector, and text workflows | 87 tests, all PASS | Rust/data/proof primitives |

---

## Public Safety Rule

Do not publish raw internal handbooks unless each one is reviewed for sensitive paths, private claims, internal architecture details, exploit-adjacent implementation detail, customer assumptions, and proprietary strategy.

The recruiter repo should summarize the systems; it should not become a dump truck of internal doctrine.
