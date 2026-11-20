# Playwright regression case study · 20 November 2026

**Objective:** Add repeatable browser-level regression checks to a real Razorglint website source snapshot without contacting production systems.

## What was built

- Python `pytest-playwright` / Chromium tests that start a temporary server bound to `127.0.0.1` and exercise the **checked-out** HTML.
- Assertions for homepage title and visible heading, pricing navigation, and legal page titles.
- Three mobile viewport checks at 390 px, including an assertion against horizontal document overflow.
- HTTP checks for an existing page (`200`, HTML content-type and expected content) and a deliberately missing page (`404`).
- GitHub Actions execution on a pull request, with JUnit results and failure-only Playwright screenshot/trace retention.

## Exact recorded result

| Field | Recorded value |
| --- | --- |
| Date | 2026-11-20 |
| System under test | Razorglint website **repository snapshot**; not the production website |
| CI | GitHub Actions, Ubuntu runner, Python 3.12, Chromium |
| Result | **9 passed, 0 failed, 1 pytest deprecation warning** |
| Test execution time | **5.41 s** |
| Source | Private draft PR #13, head `0d9b4bca15d5d4009c64c64ba871c7fd6ca16cf3` |
| Publishing state | **Draft PR. Not merged or deployed.** |

The run and source are in a **private** repository. Their full logs and code are not public proof links; they can be reviewed under authorized access. This page is a non-confidential description of the observed result, not an independently reproducible public test package.

## Engineering significance

The tests assert browser behavior, navigation and failure responses rather than relying on a screenshot or a successful server launch. A missing-page test confirms that a negative path is reported as a failure response. The mobile checks exercise actual layout width, not merely the presence of a viewport tag.

The work was produced in an **AI-assisted engineering workflow** and checked by executing real CI. This is not presented as personally hand-coded unaided work.

## Not established

These tests do **not** qualify a JSON application API, production availability, WCAG conformance, payment integration, authentication, a real customer environment, long-running flaky-test mitigation or security certification. One clean run does not prove sustained QA delivery across a large production test estate.

**Next justified extension:** add a real local API integration target or cross-state UI regression only where a concrete product workflow requires it. No speculative framework rollout.
