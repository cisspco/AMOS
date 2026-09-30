# AMOS IOC Tracker

**Last updated:** 2026-09-30 UTC

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 143 | 8 |
| IPs | 9 | 4 |
| SHA-256 hashes | 5 | 0 |
| **Total** | **157** | **12** |

## Blocklist URLs (raw, direct import)

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only IOCs verified by successfully fetched vendor reports. Do NOT import `unverified-domains.txt` or `unverified-ips.txt` directly into production blocking infrastructure without further validation.

| File | Contents |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2 domains — sorted, deduped, un-defanged |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IPs — sorted, deduped, un-defanged |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets / blocked fetches only) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets / blocked fetches only) |

## Latest Snapshot
See [`latest.md`](latest.md) for the full current IOC report, campaign summaries, and source attribution.

## Snapshots Archive
Daily snapshots are stored in [`snapshots/`](snapshots/).

## About
Automated daily tracker for AMOS (Atomic macOS Stealer) infrastructure IOCs, maintained for defensive blocking purposes. IOCs are sourced from vendor threat intelligence reports and classified as **verified** (body of a successfully fetched report) or **unverified** (search snippet or blocked fetch only).
