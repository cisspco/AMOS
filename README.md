# AMOS / Atomic macOS Stealer — IOC Tracker

**Last updated:** 2026-10-21 UTC (automated daily snapshot)

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 27 |
| IPs | 9 | 17 |
| SHA-256 hashes | 5 | 3 |
| **Total IOCs** | **162** | **47** |

## Blocklist files (raw, firewall-ready)

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole** — they contain only verified IOCs explicitly attributed to AMOS/Atomic Stealer in successfully fetched reports.

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains — firewall/DNS safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs — firewall safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) — review before blocking |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — review before blocking |

## Latest snapshot
See [`latest.md`](latest.md) for the full daily report including campaign summaries, persistence artifacts, and hashes.

## Snapshots archive
Daily snapshots are stored in [`snapshots/`](snapshots/).

## Data sources
Primary source: Microsoft Security Blog (fetched). All other vendor domains (Unit42, Darktrace, Hunt.io, ransom-isac.org, moonlock.com, etc.) are blocked by the egress proxy and contribute only unverified IOCs from search snippets.
