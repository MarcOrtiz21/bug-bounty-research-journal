# Responsible Disclosure

## Rules We Follow

- Read the program scope before testing.
- Do not test against production systems unless explicitly permitted.
- Keep active vulnerability details private.
- Use benign proof-of-concept payloads.
- Avoid data access beyond what is needed to demonstrate impact.
- Report promptly through the expected channel.
- Do not publish exploit steps until disclosure is permitted.

## Public Writing Standard

Pending findings may be summarized only at a high level:

- target family;
- vulnerability class;
- status;
- non-sensitive lesson learned.

Technical details are held until one of these is true:

- the report is publicly disclosed by the platform;
- a CVE/advisory is published;
- the maintainer explicitly approves publication;
- the vulnerability is already remediated and disclosure terms allow publication.

## Secret Handling

Never publish:

- API tokens;
- private keys;
- `.env` files;
- private report URLs;
- unpublished PoCs;
- exploit chains for unresolved findings.
