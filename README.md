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

## How I Work

I start with scope and payout clarity, then check public duplicate noise before spending time on a target. If the idea survives that filter, I build a small threat model, trace source-to-sink paths, and validate with a focused reproduction.

I try to keep severity honest. A clean medium-severity report is better than an inflated high-severity report that collapses during triage.

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
