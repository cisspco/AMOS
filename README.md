# AMOS IOC Tracker

**Last updated:** 2026-09-19 UTC

Defensive blocking lists for AMOS / Atomic macOS Stealer infrastructure, updated daily from vendor threat intelligence reports.

## Counts (cumulative, this run)
| Category | Count |
|---|---|
| Verified domains | 143 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 7 |
| Unverified IPs | 4 |

## Blocklist files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** The `unverified-*` files contain indicators sourced only from search snippets or blocked reports and should be reviewed before operational use.

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2/delivery domains — firewall-safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IPs — firewall-safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (review before blocking) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (review before blocking) |

## Latest snapshot
See [`latest.md`](latest.md) for the full IOC report including hashes, persistence artifacts, campaign summaries, and sourcing.

## Raw blocklist URLs (for direct import)
```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Methodology
- IOCs are classified **verified** (extracted from a successfully fetched vendor report) or **unverified** (search snippet or blocked fetch only).
- Blocklists are cumulative — entries are never dropped unless a fetched report explicitly confirms sinkhole/takedown.
- All IOC mentions in reports are defanged (`example[.]com`); blocklist files contain raw un-defanged values for direct import.
- Sources prioritized: Microsoft Security Blog, Palo Alto Unit 42, Malwarebytes, Sophos, Jamf, Darktrace, IRU, Moonlock, Intego, CISA.
