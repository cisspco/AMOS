# AMOS IOC Tracker

**Last updated:** 2026-11-08 UTC

Defensive blocking resource for Atomic macOS Stealer (AMOS) infrastructure. Updated daily via automated snapshot runs.

## Counts (cumulative)
| List | Count |
|------|-------|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 32 |
| Unverified IPs | 23 |
| Unverified hashes (SHA-256) | 3 |
| Unverified hashes (MD5) | 2 |

## Blocklist files

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole** — they contain only verified IOCs (sourced from successfully fetched vendor reports). The `unverified-*.txt` files require additional validation before operational use.

| File | Description |
|------|-------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains — firewall-ready |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs — firewall-ready |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets only) |

## Latest snapshot
See [`latest.md`](latest.md) for the full current snapshot with defanged IOCs, campaign summaries, and source attribution.

## Snapshots archive
Daily snapshots are stored in [`snapshots/`](snapshots/).

## Notes
- IOCs marked ⚠️ are unverified (search snippet only) and must not be used directly in production blocklists without further validation.
- IOCs marked 🔥 appeared in a report dated within the last 7 days.
- All egress fetches are blocked in the automated environment; all IOCs since 2026-11-01 are therefore unverified pending a network policy change.
- AMOS infrastructure rotates rapidly; treat older entries (pre-2026) with lower confidence.
