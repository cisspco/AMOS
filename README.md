# AMOS / Atomic macOS Stealer IOC Repository

**Last updated:** 2026-11-14 UTC (automated daily snapshot)

## Counts
| List | Count |
|------|-------|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 32 |
| Unverified IPs | 26 |
| Unverified hashes (SHA-256 + MD5) | 5 |

## Blocklist URLs (raw, for firewall/DNS sinkhole import)

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall.** These contain only IOCs verified in a successfully fetched vendor report. The `unverified-*.txt` files require human review before operational use.

| File | Description |
|------|-------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains — firewall-safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs — firewall-safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets / blocked fetches) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets / blocked fetches) |

## Daily Snapshots
Full reports with defanged IOCs, campaign context, and change log are in [`snapshots/`](snapshots/).

The latest snapshot is always at [`latest.md`](latest.md).

## Notes
- IOCs are cumulative. Entries are only removed when a fetched report explicitly confirms sinkhole or takedown.
- All blocklist files are un-defanged, sorted, and deduplicated.
- AMOS infrastructure rotates rapidly; treat older indicators as lower confidence.
- Blocked vendor domains this run: cyera.com, ransom-isac.org, moonlock.com (not in session's allowed network domains).
