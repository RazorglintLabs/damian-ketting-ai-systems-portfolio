# Selected Engineering Case Studies — 16 October 2026

These are **design/build cases**, not claims of deployments into named customers. See [dated evidence register](CURRENT_RESULTS_2026-10-16.md).

## 1. Compliance Drift Detector — Making checkpoint drift legible
**Pain:** A policy can appear healthy today while an earlier observation showed a below-threshold state.  
**Approach:** Structured operator-supplied claims/observations; deterministic classifications; history and recovery display; separate report/evidence JSON consistency verification.  
**Observed result:** 76 test regressions in linked Oct 16 Windows/Linux CI and accepted unsigned portable Windows preview, using synthetic example input.  
**Not shown:** raw-log intelligence, data-source authenticity, continuous collection or certification.  
**Skills:** Python, CSV/JSON workflow, GUI packaging, reporting, verification, platform CI.

## 2. Prestige-Reforged — An evidence boundary for claims
**Pain:** A report or marketing claim can drift away from the exact inputs and source state supposedly supporting it.  
**Approach:** Model source identity, evidence custody, evaluation, historical transitions and claim readiness separately. Require explicit acceptance rather than converting incomplete proof into PASS.  
**Status:** Private staged engineering. Desktop UI/search and installer acceptance still under review, not a general release.  
**Skills:** deterministic architecture, test-driven development, evidence governance, acceptance gates.

## 3. Command Guardian — Receipts for terminal safety
**Pain:** Blocking a dangerous command without an explainable record is a weak operating control.  
**Approach:** Deny-first classification, tested bypass corrections and SHA-256 chained receipts with sanitization.  
**Observed result:** Historical 131-test passing snapshot from April 2026.  
**Not shown:** complete command safety, digital signatures, SAR integration or production readiness.  
**Skills:** security-aware CLI engineering, adversarial fixtures, receipts, bounded claims.

## 4. Viventia + VEAC — Separation of product from examiner
**Pain:** Software should not declare its own overall security simply because its happy-path suite passed.  
**Approach:** Product focuses on scoped operational evidence; a separate adversarial examiner retains campaign scopes, hostile cases and target identity.  
**Status:** Private work in development; an examiner's CLEAR result is never a certificate.  
**Skills:** threat-boundary separation, source provenance, hostile testing, operator-centered assurance design.
