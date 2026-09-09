# RED OPS Security Manual — Public Preview

**Created and published by [@Michel-DV](https://github.com/Michel-DV).**  
Official project: **https://github.com/Michel-DV/red-ops-security-manual**

This repository is intentionally a **small public preview** of the RED OPS Security Manual. It is designed to show the structure, editorial direction, and assessment workflow without publishing complete operational chapters, full field cards, or the private source/build tree.

## Assessment workflow

```text
SCOPE
  ↓
OSINT & EXTERNAL RECON
  ↓
NETWORK DISCOVERY & ENUMERATION
  ↓
WEB CONTENT DISCOVERY
  ↓
INITIAL ACCESS / VALIDATION
  ↓
POST-EXPLOITATION & PRIVILEGE ESCALATION
  ↓
ACTIVE DIRECTORY
  ↓
CREDENTIAL TESTING
  ↓
WIRELESS AUDITING
  ↓
EVIDENCE, HAND-OFFS & REPORTING
```

The manual is built around **phase hand-offs** rather than isolated cheat sheets: each section explains what information should move into the next phase and what should be recorded for reporting.

## Complete Edition structure

The commercial Complete Edition contains seven connected guides:

1. **OSINT & External Recon** — public-source discovery, subdomain enumeration, exposed-asset research, and recon hand-off.
2. **Nmap / Network Recon** — host discovery, port mapping, service fingerprinting, NSE-based enumeration, timing, and reporting.
3. **Web Content Discovery** — ffuf, Feroxbuster, and Gobuster workflows for paths, vhosts, parameters, filtering, and output.
4. **Post-Exploitation & Privilege Escalation** — Metasploit, Searchsploit, Meterpreter, Linux/Windows enumeration, and post-access workflow.
5. **Active Directory Tooling** — BloodHound, NetExec, Impacket, relationship mapping, and AD assessment workflow.
6. **Credential Testing & Cracking** — Hydra, John the Ripper, Hashcat, online/offline distinctions, and cracking workflow.
7. **Wireless Auditing** — Aircrack-ng, hcxtools, Wifite, capture concepts, and wireless assessment workflow.

The Complete Edition also includes a **107-page connected manual**, **7 standalone guide PDFs**, and **28 pages of RED OPS Field Cards**.

## Field-reference design

RED OPS uses a consistent page system across the whole manual:

- **PHASE** — where the technique fits in the engagement.
- **GOAL** — what the operator is trying to establish.
- **FIELD TIP** — practical workflow advice.
- **SCOPE CHECK** — authorization or production-impact considerations.
- **WATCH OUT** — lockout, noise, reliability, or operational risk.
- **VERSION NOTE** — syntax or behavior that may differ between releases.
- **NEXT MOVE →** — what evidence should feed the next phase.

This is intended to make the manual useful as a **second-screen field reference**, not just something read once from beginning to end.

## What is intentionally not public

The public repository does **not** contain:

- complete operational chapters;
- the full Nmap, web, AD, credential, post-exploitation, or wireless references;
- complete field-card sets;
- the private technical-review notes;
- the editorial source tree and build system;
- the customer Complete Edition package.

That separation is deliberate. GitHub is the official project home and preview surface; the Complete Edition remains a separately distributed commercial product.

## Authorship and provenance

The commercial PDFs carry **Michel-DV** on the publication/license page and back cover, and use **Michel-DV** as the embedded PDF author metadata. Official release packages include SHA-256 checksums so buyers can verify the files they received against the publisher's release set.

## Authorized use

RED OPS is written for scoped penetration tests, controlled labs, CTF environments, owned infrastructure, and security training. Nothing in this repository grants permission to test third-party systems.

## Version

**RED OPS Security Manual v1.0.0**  
Released: **2026-09-09**

See [README.md](README.md) for the project overview and [LICENSE.md](LICENSE.md) for public-repository terms.
