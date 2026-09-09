# AMOS IOC Repository

**Last updated:** 2026-09-09 UTC

## Counts
| Category | Count |
|---|---|
| Verified domains | 140 |
| Verified IPs | 8 |
| Verified hashes (SHA-256) | 4 |
| Unverified domains | 7 |
| Unverified IPs | 3 |
| **Total IOCs** | **162** |

## Blocklist URLs (raw, for firewall/DNS import)

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | **VERIFIED** domains — safe to feed directly into a firewall/DNS sinkhole |
| [`blocklists/ips.txt`](blocklists/ips.txt) | **VERIFIED** IPs — safe to feed directly into a firewall |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search-snippet sources only) — review before blocking |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — review before blocking |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without additional vetting.**

## Latest Snapshot
See [`latest.md`](latest.md) for the full current report, or browse [`snapshots/`](snapshots/) for historical daily reports.

## About
Daily automated IOC tracking for **AMOS / Atomic macOS Stealer** for defensive blocking purposes. All entries are explicitly attributed to AMOS or known direct variants. IOCs sourced only from search snippets are marked unverified and kept in separate lists.
