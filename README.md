# AMOS IOC Feed — cisspco/AMOS

Defensive-blocking IOC repository for **AMOS / Atomic macOS Stealer** infrastructure.  
Updated daily by automated scheduled task.

**Last updated:** 2026-10-02 UTC

## Counts
| Category | Count |
|---|---|
| Verified domains | 143 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 13 |
| Unverified IPs | 8 |

## Blocklist files

| File | Description | Safe for firewall? |
|---|---|---|
| `blocklists/domains.txt` | Verified domains, un-defanged, sorted | **YES** |
| `blocklists/ips.txt` | Verified IPs, un-defanged, sorted | **YES** |
| `blocklists/unverified-domains.txt` | Unverified domains (snippet-only) | Review first |
| `blocklists/unverified-ips.txt` | Unverified IPs (snippet-only) | Review first |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.**  
> Unverified lists require manual review before operational use.

## Raw blocklist URLs (GitHub)
- Domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Snapshots
Daily snapshots (Korean, defanged) are stored in `snapshots/YYYY-MM-DD.md`.  
The most recent snapshot is always mirrored at `latest.md`.

## Verification levels
- **Verified** — IOC appeared in the body of a successfully fetched vendor report.
- **Unverified** ⚠️ — IOC sourced only from a search-result snippet or a report whose fetch was blocked. Never placed in `domains.txt` / `ips.txt`.

## Primary sources tracked
Microsoft Security Blog, Darktrace, IRU, Unit 42 (Palo Alto), Moonlock, Sophos, Hunt.io, CloudSEK, Trend Micro, Ransom-ISAC
