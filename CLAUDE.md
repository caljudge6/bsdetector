# BSDetector — Claude Code Configuration

## You are in: BSDETECTOR (`caljudge6/bsdetector`)

**Project key:** `bsd` | **Local path when accessed via WhatsApp bridge:** `/home/ubuntu/repo-bsdetector` on `rs-bots` (Hetzner Cloud, Helsinki, IP `204.168.156.4`).

This is one of Cathal Maurice Judge's six active project repos. The same WhatsApp bot serves all six; CJ binds groups to projects via `/project <key>`.

### How CJ controls this AI (universal across all 6 repos)
- **WhatsApp:** he texts `+971 585 022 883` from his personal number. Only his number is on the allowlist.
- **Cloud box:** **Hetzner Cloud CX43** (16 GB RAM, 8 cores Intel x86, 150 GB SSD, Ubuntu 24.04 LTS, ~EUR14.27/month flat).
- **Auth:** Claude Max OAuth token. NOT API credits. NOT Bedrock. NOT Vertex.
- **Bridge code:** `tools/whatsapp-bridge/index-baileys.js` in the RS repo (source of truth). Synced to the box via `rs-autosync.timer`.
- **Standing rules:** Rule #43 / Charter A5 = ultra-code mode permanently ON. Rule #44 / Charter A6 = auto mode permanently ON (no approval prompts except 4 narrow exceptions: cost >= $5/mo, irreversible destructive ops, brand/strategic decisions, genuine creative forks).

### The six repos this bot serves
| Key | Repo | Local path | This file? |
|---|---|---|---|
| `rs` | `caljudge6/DockerRepScorecard` | `/home/ubuntu/repo` | no |
| `vf` | `caljudge6/AIAfrica` | `/home/ubuntu/repo-visionforge` | no |
| `rpga` | `caljudge6/storyteller` | `/home/ubuntu/repo-rpgarchitect` | no |
| `centcom` | `caljudge6/CentCom` | `/home/ubuntu/repo-centcom` | no |
| `bsd` | `caljudge6/bsdetector` | `/home/ubuntu/repo-bsdetector` | YES |
| `ciso` | `caljudge6/CISOAssurance.ai` | `/home/ubuntu/repo-cisoassurance` | no |

### Governance hierarchy
```
CentCom (central governance, CHARTER.md source of truth)
  +-- Reputation Scorecard (rs) — consumer SaaS, reputation scoring
  +-- VisionForge (vf) — AI for Africa education platform
  +-- ArchitectRPG (rpga) — GM engine for tabletop RPGs
  +-- BSDetector (bsd) — React Native mobile boilerplate/app [THIS REPO]
  +-- CISO Assurance (ciso) — cybersecurity assurance platform
```

### Full bridge runbook
**`Claude_docs/HOW-TO/whatsapp-bridge.md`** in the RS repo (source of truth: `caljudge6/CentCom`). Covers troubleshooting, slash commands, OAuth refresh, restart procedures, recovery procedures.

---

## STEP 0 — LOAD `./CHARTER.md` FIRST (MANDATORY)

**Before reading ANY rule below, load `./CHARTER.md` in this repo.** The Charter is the single source of truth for the universal behavioural rules that apply across every company CJ runs as a solo AI-operated founder. If you skip the Charter, you skip ~70% of the rules.

This file (`CLAUDE.md`) is the BSDetector-specific OVERLAY. Where this file contradicts the Charter, the project rule wins ONLY for this project and must be explicitly marked `OVERRIDES Charter [letter-number]: [reason]`. Default: Charter wins.

**Charter source of truth:** https://github.com/caljudge6/CentCom (PRIVATE).

---

## Project Overview

BSDetector is a React Native mobile application built on the Ignite boilerplate (Infinite Red). TypeScript-based.

## Tech Stack
- **Framework:** React Native (Ignite boilerplate)
- **Language:** TypeScript
- **Platform:** iOS + Android

---

## Project-Specific Rules

(To be defined as the project evolves. All Charter rules apply by default.)
