# Bug Bounty Research Journal

I use this repository as a public, sanitized journal of my responsible-disclosure work in open-source security.

My current focus is AI/ML systems, model-file vulnerabilities, open-source security programs, and practical bounty triage. I keep the sensitive work private until disclosure is authorized, but I publish the process, methodology, and lessons that can be shared safely.

This is intentionally not a dump of private reports. I do not publish active findings, exploit details, private program URLs, proof-of-concept files, tokens, or unpublished vulnerability chains before coordinated disclosure allows it.

## What I Publish

- My methodology for selecting targets and avoiding low-signal duplicate work.
- Notes about bounty platforms and how I evaluate them.
- A high-level research timeline with sensitive details removed.
- Responsible disclosure rules I follow.
- Case-study placeholders that can become full write-ups after disclosure.

## What I Research

- AI/ML open-source security programs.
- Model-file vulnerability research.
- Scanner-bypass behavior in model/artifact formats.
- Auth, access-control, SSRF, artifact-handling, and supply-chain-adjacent classes.
- Smaller paid open-source issues when the fix is clear, low-noise, and not already saturated.

## Research Threads Touched

This is the public-safe view of the cases I have worked through. Active reports and unresolved details stay private.

| Area | Targets / Programs | Public Status |
|---|---|---|
| Paid OSS issue triage | Expensify/App, IssueHunt, Opire, Algora | Evaluated for bounty quality, duplicate noise, and time-to-fix. |
| AI/ML open-source security | Huntr AI/ML targets including chat, workflow, dashboard, and driver projects | Multiple private reviews and reports; details withheld during disclosure. |
| Model-file vulnerability research | Joblib, Keras/HDF5, SafeTensors, GGUF, tokenizers | Active research into parser behavior, scanner coverage, and safe-loading assumptions. |
| Vendor disclosure routing | AWS VDP / HackerOne-style programs | Used when a finding does not fit the primary bounty platform cleanly. |
| Alternative bounty ecosystems | Code4rena, Immunefi, Google Patch Reward Program, FreeCAD rewards | Evaluated as secondary tracks with different skill and payout profiles. |
| Parallel non-disclosure work | Patch-reward queues, paid OSS radar, scoped maintenance/support work | Kept operationally separate from active vulnerability disclosure to reduce leakage risk. |

## Case Study Queue

I keep full technical notes privately while reports are pending. Once disclosure is allowed, I plan to turn suitable findings into public write-ups covering:

- what the vulnerable trust boundary was;
- how I reduced duplicate risk;
- how the finding was validated safely;
- what remediation pattern fixed or reduced the issue;
- what I would check earlier next time.

## How I Work

I start with scope and payout clarity, then check public duplicate noise before spending time on a target. If the idea survives that filter, I build a small threat model, trace source-to-sink paths, and validate with a focused reproduction.

I try to keep severity honest. A clean medium-severity report is better than an inflated high-severity report that collapses during triage.

I also keep unrelated paid work, patch-reward queues, and public issue-bounty scouting in a separate lane so active disclosure context does not bleed into public-facing material.

## Disclosure Policy

I do not publish enough detail to reproduce an active vulnerability before the maintainer, platform, or program has cleared disclosure.

For pending findings, public notes are limited to broad category, target family, status, and lessons learned. Full technical write-ups are published only after remediation, public advisory, CVE publication, or explicit approval.

## Repository Map

- `docs/methodology.md`: how I approach target selection and validation.
- `docs/platform-notes.md`: notes on bounty platforms I have evaluated.
- `docs/target-selection.md`: scoring criteria for deciding what to attack next.
- `docs/responsible-disclosure.md`: my disclosure and secret-handling rules.
- `docs/weekly-log-sanitized.md`: public timeline with sensitive details removed.
- `case-studies/`: future public write-ups after disclosure.

## Status

This repository is a public record of process, not a live exploit archive.
