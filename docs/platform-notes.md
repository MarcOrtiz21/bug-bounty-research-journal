# Platform Notes

## Huntr

Best current fit for AI/ML and model-file vulnerability research.

Strengths:

- clear focus on AI/ML open-source security;
- meaningful payouts for strong findings;
- private reporting flow;
- CVE-oriented workflow for accepted open-source vulnerabilities.

Operational notes:

- avoid generic reports without a new exploit path;
- model-file vulnerability reports need strong PoCs and scanner/impact clarity;
- some classes, especially simple SSRF and DoS, can be downgraded or marked informative.

## HackerOne

Useful for vendor disclosure and mature programs.

Strengths:

- broad program ecosystem;
- vendor VDPs for targets that do not fit Huntr;
- established disclosure workflow.

Operational notes:

- payout is program-specific;
- many VDPs do not pay;
- account setup and program policy review are mandatory before submitting.

## IssueHunt / Open-Source Issue Bounties

Useful only when the issue is fresh, under-discussed, and has no active PR.

Strengths:

- straightforward bugfix work;
- often tied directly to GitHub issues.

Operational notes:

- many paid issues are stale or already have PRs;
- payouts can be too low for the investigation cost;
- duplicate proposals are common.

## Code4rena / Immunefi

High upside, but a different skill track.

Strengths:

- strong payouts;
- deep security work;
- public judging or structured triage in many cases.

Operational notes:

- heavy Web3/EVM/DeFi bias;
- requires dedicated Solidity and protocol-security investment;
- not the fastest path for quick open-source wins from a web/AI codebase background.
