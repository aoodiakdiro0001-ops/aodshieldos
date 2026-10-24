# Aodı Akdıro Shield OS — Cyber Defense Playbook

**The operator's handbook for real security work — one zero-dependency app, six audited modules, Arabic + English.**

Security fails in the gaps between tools: an identity provider without least privilege, an EDR without patching discipline, backups nobody has ever restored. Shield OS packages the operating layer: **75 audited records** across **6 OS modules** in a single HTML file that runs offline.

- **License:** MIT © 2026 Baran Avisat (see LICENSE)
- **Price:** $14 — lifetime license, free updates for 1 year
- **Support:** baranavisat@gmail.com · WhatsApp +90 531 326 37 22 (wa.me/905313263722)
- **Product line:** Aodı Akdıro Suite — github.com/aoodiakdiro0001-ops

## What's inside (6 modules)

| Module | Records | What you get |
|---|---|---|
| 🛡️ **Defense Map** | 12 | Identity platform (Okta/Ping-style), secrets vault, behavioral EDR (CrowdStrike-style), device + patch management, packet analyzer (Wireshark-style), vulnerability scanner (Nessus-style), deny-by-default firewall, zero-trust access gateway, log aggregation (SIEM), phishing simulation platform, vulnerability management, tested backups |
| ⚙️ **Defense Pipelines** | 10 | Employee onboarding with signed access list, vendor access with expiry, offboarding in one hour, suspect-device triage, monthly patch cycle, vulnerability remediation deadlines, incident response, quarterly access review, restore drill, monthly phishing drill |
| 📜 **Defense Contracts** | 8 | Vulnerability report, incident report, access matrix, audit plan, log-hunt briefing, password policy, monthly security posture, monthly security documentation |
| 🗓️ **21-Day Plan** | 21 | Inventory → identity → endpoints → network → testing → governance, one day = one move with a KPI |
| 🧮 **Security Cost Calculator** | 6 fields | NetSec×Sender×« »×Scheduler— Protection cost = endpoints × price, identity seats, yearly pentest ÷ 12, log storage — monthly burn with the biggest driver named |
| 🛡️ **Defense Policy** | 18 | 2FA everywhere, least privilege, one secrets vault, no sharing, key rotation, registered devices, offline-capable backups, disk encryption, incident runbook, quarterly reviews, vendor security clauses |

**75 records, all checked by the automated auditor** (contract counts, empty fields, encoding hygiene) before shipping.

## Why this is different

1. **Operations, not fear.** Every card is a move you can make this week — pointers, execution bullets, honest trade-offs.
2. **Anti-hype stance.** The app itself warns: pricing and capabilities change — vendor docs win; the map helps you choose, not replace.
3. **One file. No dependencies.** `app/index.html` runs offline from any browser.
4. **Bilingual.** Arabic + English toggle, RTL-aware.
5. **Your data stays yours.** localStorage (`aos_aodshieldos_*`), JSON export, per-module CSV.

## Quick start

1. Open `app/index.html` in any modern browser (double-click works).
2. Start with **21-Day Plan** → day 1 (asset + owner inventory).
3. Work **Defense Policy** high-risk items before anything public-facing.

## What's in the package

```
app/          index.html — the full app (single file, offline)
export/       aodshieldos.json + one CSV per module
library/      one Markdown reference sheet per module
docs/         screenshots
README.md, START_HERE.md, POLICY.md, CHANGELOG.md, LICENSE
content.py, contract.json (source of truth) · build.py, check.py (auditor)
```

## Honest disclosure

- The calculator is an **estimate** — read your vendor's current pricing.
- The policy is a strong starting draft; make it official after your own review.
- The Defense Map helps you **compare faster**; it does not replace vendor docs or certified assessments.

© 2026 Baran Avisat · MIT License · Bitcoin `bc1q8dhtdrndxsl70e97t8grydfe6pjue37zrhzf6c` · USDT-TRC20 `TLWdTjqqogkXNEXGiPWsGdjFP6ioycxeWW`
