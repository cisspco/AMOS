# AMOS / Atomic macOS Stealer — IOC Repository

**Last updated:** 2026-09-25 UTC (automated daily snapshot)

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 143 | 7 |
| IPs | 9 | 4 |
| SHA-256 hashes | 5 | 0 |
| **Total IOCs** | **157** | **11** |

## Blocklist Files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only verified IOCs explicitly attributed to AMOS/Atomic Stealer in successfully fetched vendor reports. The `unverified-*.txt` files are for review only.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified AMOS C2/delivery domains, un-defanged, sorted | [domains.txt](blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified AMOS C2 IPs, un-defanged, sorted | [ips.txt](blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (search-snippet only) — review before blocking | [unverified-domains.txt](blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search-snippet only) — review before blocking | [unverified-ips.txt](blocklists/unverified-ips.txt) |

## Latest Snapshot

See [latest.md](latest.md) for the full current report, or browse [snapshots/](snapshots/) for daily history.

## About

This repository is updated daily by an automated scheduled task that searches threat intelligence sources and vendor reports for AMOS/Atomic macOS Stealer IOCs. All IOCs are classified as **verified** (appeared in the body of a successfully fetched vendor report) or **unverified** (search snippet only). Verified IOCs are cumulative — entries are never dropped unless a fetched report explicitly confirms sinkholing or takedown.

**Sources tracked:** Microsoft Security Blog, Palo Alto Unit 42, Malwarebytes, SANS ISC, IRU, Ransom-ISAC, Malware.news, and others.
