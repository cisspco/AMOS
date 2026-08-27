# AMOS / Atomic macOS Stealer — Defensive IOC Repository

**Last updated:** 2026-08-27 UTC (automated daily snapshot)

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 133 | 1 |
| IPs | 10 | 0 |
| SHA-256 hashes | 4 | 0 |
| **Total IOCs** | **147** | **1** |

## Blocklist Files (Firewall-Safe)

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These files contain only verified, un-defanged entries (one per line). The `unverified-*` files are for analyst review only.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified AMOS C2/delivery domains | [domains.txt](blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified AMOS C2 IPs | [ips.txt](blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (analyst review only) | [unverified-domains.txt](blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (analyst review only) | [unverified-ips.txt](blocklists/unverified-ips.txt) |

## Snapshots

Daily full reports are in `snapshots/YYYY-MM-DD.md`. The most recent is always mirrored to `latest.md`.

## About

This repository tracks Atomic macOS Stealer (AMOS) infrastructure for **defensive blocking purposes**. IOCs are sourced from public threat intelligence reports (Microsoft Security Blog, SANS ISC, Trend Micro, Brinztech, Datadog Security Labs, IRU, and others) and classified by evidence level:

- **Verified** — indicator appeared in the body of a successfully fetched report
- **Unverified** — indicator came only from a search-result snippet or a report whose fetch was blocked

Unverified IOCs are marked ⚠️ in snapshots and are never placed in the firewall-safe blocklist files.

IOCs are cumulative across runs. An entry is only removed when a fetched source explicitly confirms it has been sinkholed or taken down.
