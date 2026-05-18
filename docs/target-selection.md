# Target Selection

## Current Scoring Criteria

Targets are scored using:

- payout visibility;
- scope clarity;
- implementation familiarity;
- amount of public duplicate noise;
- proof-of-concept cost;
- likely triage risk;
- expected time to first validated finding.

## Good Signs

- Clear security boundary.
- Recently changed code.
- Few public reports in the same class.
- Practical exploit path with a realistic victim action.
- Program explicitly rewards the affected category.

## Bad Signs

- Many recent similar reports.
- Only local crashes with no security impact.
- Generic unsafe deserialization without a new bypass or threat model.
- Maintainer has already documented the behavior as intended.
- Fix requires broad architecture changes with uncertain ownership.

## Current Research Buckets

- Model-file scanner bypasses.
- AI/ML artifact loading and parsing.
- Access-control mistakes in AI platforms.
- SSRF only when impact goes beyond blind or limited fetch behavior.
- Paid OSS fixes only when low-noise and obvious enough to justify the time.
