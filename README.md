# AMOS / Atomic macOS Stealer — IOC Repository

**Last updated:** 2026-09-18 UTC  
**Verified domains:** 143 | **Verified IPs:** 9 | **Unverified domains:** 7 | **Unverified IPs:** 4 | **Hashes:** 5

Automated daily snapshots of AMOS (Atomic macOS Stealer) indicators of compromise for defensive blocking. All IOCs are explicitly attributed to AMOS or confirmed AMOS-delivering infrastructure.

## Blocklist files

| File | Contents | Safe to feed into a firewall? |
|------|----------|-------------------------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS domains, un-defanged, sorted | **Yes** |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS IPs, un-defanged, sorted | **Yes** |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (snippet-only sourcing) | Review before use |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (snippet-only sourcing) | Review before use |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without manual review.**

## Snapshots

Full daily reports (Korean, defanged) are in [`snapshots/`](snapshots/). The latest report is always at [`latest.md`](latest.md).

## Evidence levels

- **verified** — IOC appeared in the body of a successfully fetched vendor report
- **unverified** — IOC sourced only from a search-result snippet or from a report whose fetch was blocked

Unverified IOCs are tracked in `unverified-*.txt` files. When a later run fetches a confirming report, the entry is promoted to the verified list.
