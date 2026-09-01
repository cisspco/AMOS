# AMOS / Atomic macOS Stealer — IOC Blocklist Repository

**Last updated:** 2026-09-01 UTC  
**Maintained by:** Automated daily snapshot (defensive tracking)

## Counts (2026-09-01)

| Category | Verified | Unverified |
|---|---|---|
| Domains | 140 | 7 |
| IPs | 8 | 2 |
| SHA-256 hashes | 4 | 0 |
| **Total** | **152** | **9** |

> **Verified** = indicator appeared in the body of a successfully fetched vendor report.  
> **Unverified** = indicator sourced only from a search-result snippet, or from a report whose fetch was blocked (EGRESS_BLOCKED). Do **not** feed unverified lists directly into production firewalls without manual review.

## Safe-to-block files (verified only)

These two files are the **only files safe to feed directly into a firewall or DNS sinkhole**:

- [`blocklists/domains.txt`](blocklists/domains.txt) — 140 verified C2/delivery domains, one per line, un-defanged
- [`blocklists/ips.txt`](blocklists/ips.txt) — 8 verified C2 IP addresses, one per line, un-defanged

## Unverified (review before use)

- [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) — 7 domains, unconfirmed source
- [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) — 2 IPs, unconfirmed source

## Daily snapshots

Full Korean-language IOC reports with context, source attribution, and change log:

- [`latest.md`](latest.md) — most recent snapshot
- [`snapshots/`](snapshots/) — historical archive by date (YYYY-MM-DD.md)

## Scope

This repository tracks **AMOS (Atomic macOS Stealer)** and its directly attributed variants only. IOCs from other macOS infostealers (MacSync, Shub, Infiniti, etc.) are excluded unless explicitly co-attributed to AMOS in the source report.

## Attribution policy

- All blocklist files are cumulative and deduplicated.
- An IOC is dropped only when a successfully fetched report in the same run explicitly reports it sinkholed or taken down.
- When an unverified entry is confirmed by a fetched report in a later run, it is promoted: removed from `unverified-*.txt` and added to the verified file.
