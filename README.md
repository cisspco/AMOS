# AMOS / Atomic macOS Stealer — Defensive IOC Repository

**Last updated:** 2026-10-23 UTC  
**Maintained by:** Automated daily snapshot (defensive blocking purposes)

## Counts

| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 27 |
| IPs | 9 | 17 |
| SHA-256 hashes | 5 | 3 |
| **Total** | **162** | **47** |

## Blocklist Files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only verified IOCs from successfully fetched vendor reports. The `unverified-*` files are for analyst review only.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified domains — firewall/DNS safe | [domains.txt](blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified IPs — firewall safe | [ips.txt](blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only) — analyst review | [unverified-domains.txt](blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets only) — analyst review | [unverified-ips.txt](blocklists/unverified-ips.txt) |

## Daily Snapshots

Full IOC reports with context, campaign summaries, and change logs are in [`snapshots/`](snapshots/).  
The most recent snapshot is always at [`latest.md`](latest.md).

## IOC Classification

- **Verified**: Indicator appeared in the body of a successfully fetched vendor report
- **Unverified** ⚠️: Indicator came only from a web search result snippet, or from a report whose fetch was blocked (EGRESS_BLOCKED)

## Primary Sources

- Microsoft Security Blog — macOS ClickFix campaign research (2026-05-06, 2026-08-05)
- Unit 42 / Palo Alto Networks — AMOS stealer activity (2026, fetch blocked)
- IRU — AMOS ClickFix/Odyssey analysis (2026, fetch blocked)
- Moonlock — AMOS AI agent tool impersonation (2026, fetch blocked)
- Ransom-ISAC, CloudSEK, Darktrace, infostealers.com — additional campaign intelligence (search snippets, unverified)

## Format Notes

All IOCs in snapshot reports are **defanged** (`example[.]com`, `1.2.3[.]4`).  
Blocklist `.txt` files are **un-defanged**, one entry per line, sorted, deduplicated.
