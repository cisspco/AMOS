# AMOS / Atomic macOS Stealer — IOC Tracker

**Last updated:** 2026-09-27 UTC

| Category | Verified | Unverified |
|---|---|---|
| Domains | 143 | 7 |
| IPs | 9 | 4 |
| SHA-256 hashes | 5 | 0 |
| **Total IOCs** | **157** | **11** |

## Blocklist files (firewall-safe)

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** The `unverified-*` files contain indicators sourced only from search snippets or blocked reports and must be reviewed before operational use.

| File | Content | Raw URL |
|---|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2 domains, un-defanged, sorted | `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt` |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IPs, un-defanged, sorted | `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt` |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (review before use) | `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt` |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (review before use) | `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt` |

## Latest snapshot

See [`latest.md`](latest.md) for the full daily report including campaign summaries, hashes, persistence artifacts, and change log.

Historical snapshots are in [`snapshots/`](snapshots/).

## About

Automated daily defensive IOC tracker for AMOS (Atomic macOS Stealer) infrastructure. IOCs are sourced from vendor threat reports (Microsoft, Unit 42, Intego, IRU, SANS ISC, etc.) and classified as **verified** (appeared in a successfully fetched report body) or **unverified** (search snippet only). Runs daily via scheduled Claude Code session.
