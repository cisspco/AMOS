# AMOS IOC Repository

**Last updated:** 2026-10-22 UTC

## Counts
| List | Entries |
|------|---------|
| Verified domains (`blocklists/domains.txt`) | 148 |
| Verified IPs (`blocklists/ips.txt`) | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains (`blocklists/unverified-domains.txt`) | 27 |
| Unverified IPs (`blocklists/unverified-ips.txt`) | 17 |
| Unverified SHA-256 hashes | 3 |

## Raw Blocklist URLs (GitHub)

- Verified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- Verified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## ⚠️ Firewall Safety Note

**Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only verified IOCs confirmed in successfully-fetched vendor reports. The `unverified-*` files contain IOCs sourced from search snippets or blocked report fetches and carry higher false-positive risk.

## Files

- `latest.md` — full snapshot from the most recent daily run
- `snapshots/YYYY-MM-DD.md` — daily snapshots (one per run)
- `blocklists/domains.txt` — verified C2/delivery domains, un-defanged, sorted
- `blocklists/ips.txt` — verified C2 IPs, un-defanged, sorted
- `blocklists/unverified-domains.txt` — unverified domains (snippet-sourced)
- `blocklists/unverified-ips.txt` — unverified IPs (snippet-sourced)

## About

Automated daily snapshot of AMOS (Atomic macOS Stealer) indicators of compromise for defensive blocking purposes. IOCs are sourced from public vendor reports and web searches. All blocklist entries are cumulative — entries are never dropped unless a fetched report explicitly reports them sinkholed or taken down.
