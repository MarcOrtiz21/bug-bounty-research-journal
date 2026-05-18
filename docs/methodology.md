# Methodology

## 1. Pick Targets With Payout and Scope Clarity

Before spending time on a target, we check:

- whether the program pays cash or only reputation;
- whether the target is explicitly in scope;
- whether similar findings are already public or heavily duplicated;
- whether a one-hour investigation can realistically produce a validated result;
- whether we can explain impact without exaggerating severity.

## 2. Avoid Duplicate Classes Early

We maintain a short denylist per target: already reported issues, public CVEs, common low-value crashes, obvious DoS-only bugs, and generic unsafe-deserialization reports without a new chain.

If the likely report title already sounds like a public report, we stop or pivot.

## 3. Build a Minimal Threat Model

For each serious target:

- identify untrusted inputs;
- map trust boundaries;
- trace source-to-sink paths;
- list security assumptions made by the codebase;
- define what would count as real impact.

## 4. Validate Before Drafting

We prefer focused harnesses, unit tests, or minimal reproductions over broad claims.

A report is not ready until it has:

- affected version or commit;
- reproduction steps;
- expected versus actual behavior;
- impact narrative;
- CWE/CVSS mapping;
- remediation guidance;
- duplicate-risk notes.

## 5. Keep Severity Honest

We do not inflate CVSS to chase higher payout. A conservative report is easier to defend and less likely to be marked informative.

If triage believes impact is higher, the program can adjust severity.
