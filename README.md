# AMOS IOC Tracker

Defensive IOC feed for **AMOS / Atomic macOS Stealer** and direct variants (Odyssey).  
Updated daily by automated snapshot. All times UTC.

**Last updated:** 2026-10-10 UTC

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 24 |
| IPs | 9 | 13 |
| SHA-256 hashes | 5 | 3 |
| **Total** | **162** | **40** |

## Files

| File | Description |
|---|---|
| `latest.md` | Full snapshot with context, defanged IOCs, campaign summaries |
| `snapshots/YYYY-MM-DD.md` | Archived daily snapshots |
| `blocklists/domains.txt` | **Verified** domains — safe to feed directly into a firewall/DNS sinkhole |
| `blocklists/ips.txt` | **Verified** IPs — safe to feed directly into a firewall |
| `blocklists/unverified-domains.txt` | Unverified domains (search-snippet only) — review before blocking |
| `blocklists/unverified-ips.txt` | Unverified IPs (search-snippet only) — review before blocking |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without manual review.**  
> All entries in these two files appeared in the body of a successfully fetched vendor report.  
> Entries in `unverified-*.txt` came from search-result snippets only and have not been independently confirmed.

## Raw blocklist URLs (for firewall automation)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
```

## IOC Classification

- **verified** — appeared in the body of a successfully fetched vendor report
- **unverified** — came from a search-result snippet or a report whose fetch was blocked

## Sources (primary verified)
- [Microsoft Security Blog — ClickFix macOS (Aug 2026)](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/)
- [Microsoft Security Blog — Fake macOS utilities lures (May 2026)](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/)
