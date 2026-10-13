# AMOS / Atomic macOS Stealer IOC Repository

**Last updated:** 2026-10-13 UTC

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 24 |
| IPs | 9 | 15 |
| SHA-256 hashes | 5 | 3 |
| **Total IOCs** | **162** | **42** |

## Blocklist Files

> ⚠️ Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole. These contain **verified** entries only — each indicator appeared in the body of a successfully fetched vendor report.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified domains — un-defanged, sorted, deduped | [domains.txt](blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified IPs — un-defanged, sorted, deduped | [ips.txt](blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippet only) | [unverified-domains.txt](blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippet only) | [unverified-ips.txt](blocklists/unverified-ips.txt) |

## Daily Snapshots

Full per-run reports are in `snapshots/YYYY-MM-DD.md`. The most recent snapshot is always mirrored to `latest.md`.

## Methodology

Each run:
1. Runs 5 parallel web searches for AMOS/Atomic Stealer IOCs
2. Attempts to fetch up to 5 vendor reports (prioritising last 30–60 days)
3. Classifies IOCs as **verified** (fetched report body) or **unverified** (search snippet / blocked fetch)
4. Cumulatively merges new findings into blocklists — entries are never removed unless a fetched report confirms sinkhole/takedown
5. Commits snapshot + updated blocklists to this repository

## Primary Sources

- Microsoft Security Blog (2026-05-06, 2026-08-05) — fetched ✓
- Ransom-ISAC (2026-07+) — blocked by egress proxy
- Palo Alto Unit 42 (2026-09-16) — blocked by egress proxy
- Darktrace (2026) — blocked by egress proxy
- dev.to incident report (2026-10-02) — blocked by egress proxy
