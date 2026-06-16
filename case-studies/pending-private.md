# Pending Private Findings

Several findings are currently private through authorized disclosure workflows.

Public details are intentionally withheld until the relevant platform, maintainer, or vendor allows disclosure.

## Lessons Learned So Far

- A clean report is more valuable than a dramatic one.
- Duplicate-risk analysis should happen before building a reproduction.
- Scanner bypass work needs a precise explanation of what the scanner misses and why the runtime still reaches the payload.
- For SSRF-like findings, blind or limited reachability is usually not enough.
- Model-file vulnerability research benefits from pairing runtime behavior with scanner behavior.
- Some promising targets are worth dropping early once the duplicate noise or impact ceiling becomes obvious.
- Keeping public issue-bounty triage separate from private disclosure work reduces accidental leakage and context-mixing.
- Waiting for explicit program approval can be the correct move when a public contribution track is reward-gated or assignment-based.
