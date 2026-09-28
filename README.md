# AMOS / Atomic macOS Stealer — Defensive IOC Repository

**Last updated:** 2026-09-28 UTC

| Category | Count |
|---|---|
| Verified domains | 143 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 8 |
| Unverified IPs | 4 |

## Blocklist files

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** They contain only verified IOCs explicitly attributed to AMOS/Atomic Stealer in successfully fetched vendor reports. The `unverified-*.txt` files are for analyst review only.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified C2/delivery domains — firewall-safe | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified C2 IPs — firewall-safe | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only) — analyst review | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets only) — analyst review | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt) |

## Snapshots

Daily full-detail snapshots (Korean, defanged) are in `snapshots/YYYY-MM-DD.md`. The latest snapshot is always at `latest.md`.

## Methodology

- IOCs are included only when explicitly attributed to AMOS / Atomic Stealer (or direct variants like Odyssey when explicitly linked).
- **Verified** = appeared in the body of a successfully fetched vendor report.
- **Unverified** = appeared only in a search result snippet or in a report whose fetch was blocked.
- Blocklists are cumulative: entries are never dropped unless a fetched report explicitly confirms sinkholing or takedown.
- All four blocklist files are deduplicated and sorted on every run.
