# AMOS / Atomic macOS Stealer — IOC Tracker

**Last updated:** 2026-09-16 UTC  
**Verified domains:** 143 | **Verified IPs:** 9 | **Unverified IOCs:** 10 (7 domains, 3 IPs) | **SHA-256 hashes:** 5

Automated daily snapshot of indicators of compromise (IOCs) explicitly attributed to AMOS / Atomic macOS Stealer and known direct variants (e.g. SHAMOS), maintained for defensive blocking purposes.

## ⚠️ Safe-to-firewall files

Only these two files are safe to feed directly into a firewall or DNS sinkhole — they contain only **verified** entries (confirmed by successfully fetched vendor reports), one entry per line, un-defanged:

| File | Contents |
|------|----------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2 / delivery domains |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IP addresses |

The `unverified-*.txt` files are for research reference only — entries have not been confirmed by a directly fetched report and **must not** be added to production blocklists without independent verification.

## Raw blocklist URLs (for scripted ingestion)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Repository structure

```
snapshots/          # Daily IOC reports (YYYY-MM-DD.md), Korean, defanged
latest.md           # Most recent snapshot (same content as latest snapshot)
blocklists/
  domains.txt             # VERIFIED domains, un-defanged, sorted
  ips.txt                 # VERIFIED IPs, un-defanged, sorted
  unverified-domains.txt  # Unverified domains (research only)
  unverified-ips.txt      # Unverified IPs (research only)
README.md           # This file
```

## Methodology

- IOCs are sourced by daily automated searches across threat intelligence vendors (Microsoft, Trend Micro, Hunt.io, Sophos, Malwarebytes, IRU, Moonlock, Darktrace, Brinztech, CIS, and others).
- Only IOCs **explicitly attributed** to AMOS / Atomic Stealer (or confirmed direct variants) are included.
- IOCs are classified as **verified** (confirmed by a successfully fetched report) or **unverified** (from search snippets or blocked fetch sources).
- Blocklists are **cumulative** — entries are only removed when a fetched source explicitly reports takedown or sinkholing.
- All IOCs in the snapshot reports are defanged (e.g. `example[.]com`, `1.2.3[.]4`); blocklist `.txt` files contain raw un-defanged values.

## Primary verified sources

- [Microsoft Security Blog — ClickFix "Cloaked Gates" campaign](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/) — 2026-08-05
- [Microsoft Security Blog — ClickFix macOS Utilities Lures](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/) — 2026-05-06
- [Microsoft Security Blog — Infostealers without Borders](https://www.microsoft.com/en-us/security/blog/2026/02/02/infostealers-without-borders-macos-python-stealers-and-platform-abuse/) — 2026-02-02
