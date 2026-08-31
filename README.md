# AMOS / Atomic macOS Stealer — Defensive IOC Repository

**Last updated:** 2026-08-31 UTC (automated daily snapshot)

## Counts
| Category | Count |
|---|---|
| Verified domains | 140 |
| Verified IPs | 7 |
| Unverified domains | 7 |
| Unverified IPs | 3 |
| SHA-256 hashes | 4 |
| MD5 hashes | 0 |

## Blocklist files (raw, firewall-ready)

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** All entries are verified (sourced from a successfully fetched vendor report), un-defanged, sorted, and deduplicated. The `unverified-*.txt` files are for threat-intel review only and must NOT be deployed to production blocking infrastructure without independent verification.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified C2/delivery domains | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt |
| `blocklists/ips.txt` | Verified C2 IPs | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt |
| `blocklists/unverified-domains.txt` | Unverified domains (review before blocking) | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt |
| `blocklists/unverified-ips.txt` | Unverified IPs (review before blocking) | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt |

## Latest full report
See [`latest.md`](./latest.md) for the full daily snapshot including campaign summaries, hashes, persistence artifacts, and sourcing.

## Snapshots archive
Historical daily snapshots are in the [`snapshots/`](./snapshots/) directory.

## Attribution policy
IOCs are included only when explicitly attributed to AMOS / Atomic Stealer (or confirmed direct variants) in a successfully fetched vendor report. Search-snippet-only sources are marked unverified and held in `unverified-*.txt`. MacSync Stealer infrastructure (a co-deployed but distinct threat) is tracked separately and not included here.
