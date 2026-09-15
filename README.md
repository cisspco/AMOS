# AMOS / Atomic macOS Stealer — IOC Repository

**Last updated:** 2026-09-15 UTC  
**Verified domains:** 143 | **Verified IPs:** 9 | **Unverified domains:** 7 | **Unverified IPs:** 3 | **SHA-256 hashes:** 5

This repository tracks indicators of compromise (IOCs) for AMOS (Atomic macOS Stealer) and its confirmed direct variants for **defensive blocking purposes only**.

## Blocklist Files

| File | Description | Safe for firewall/DNS? |
|------|-------------|------------------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains, un-defanged, sorted | **YES** |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs, un-defanged, sorted | **YES** |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) | Review first |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets only) | Review first |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without manual review.**

## Raw Blocklist URLs (GitHub)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Snapshots

Daily full snapshots are written to [`snapshots/`](snapshots/) in Korean with defanged IOCs.  
[`latest.md`](latest.md) always contains the most recent snapshot.

## IOC Evidence Levels

- **Verified** — indicator appeared in the body of a successfully fetched vendor report
- **Unverified** ⚠️ — indicator came only from a search-result snippet or a report whose fetch was blocked; marked with ⚠️ `(미검증)` in snapshots
- 🔥 — indicator observed in a report dated within the last 7 days

## Sources (Primary)

- Microsoft Security Blog — ClickFix macOS campaigns (2026-02, 2026-05, 2026-08)
- Hunt.io — ATOMIC Stealer tracker
- IRU — AMOS threat intelligence
- Trend Micro — OpenClaw/ClawHub campaign
- malware.news — Community infection reports

## Methodology

All IOCs are explicitly attributed to AMOS / Atomic macOS Stealer (or confirmed direct variants). Blocklists are cumulative — entries are only removed when a successfully fetched source reports sinkholing or takedown. Entries sourced only from search snippets are never placed in the verified blocklists.
