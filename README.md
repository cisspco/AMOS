# AMOS IOC Repository

**Last updated:** 2026-10-06 UTC

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 14 |
| IPs | 9 | 9 |
| SHA-256 hashes | 5 | 3 |
| **Total** | **162** | **26** |

## Blocklist Files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only verified indicators. Do NOT feed `unverified-*.txt` files into production blocking without independent validation.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified AMOS C2 domains (un-defanged, sorted) | [`blocklists/domains.txt`](blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified AMOS C2 IPs (un-defanged, sorted) | [`blocklists/ips.txt`](blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only) | [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets only) | [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) |

## Latest Snapshot
See [`latest.md`](latest.md) for the full daily report including campaign summaries, file hashes, persistence artifacts, and source attribution.

## Snapshots Archive
Daily snapshots are stored in [`snapshots/`](snapshots/).

## Methodology
- **Verified**: IOC appeared in the body of a successfully fetched vendor report
- **Unverified** ⚠️: IOC sourced only from a search-result snippet or from a blocked report
- IOCs observed in reports dated within the last 7 days are marked 🔥
- Blocklists are cumulative — entries are only removed when a successfully fetched source explicitly reports sinkhole or takedown
- All IOCs must be explicitly attributed to AMOS / Atomic macOS Stealer (or direct variants like Odyssey when source links them explicitly)
