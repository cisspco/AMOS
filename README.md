# AMOS / Atomic macOS Stealer IOC Repository

**Last updated:** 2026-11-17 UTC  
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified hashes (SHA-256):** 5  
**Unverified domains:** 34 | **Unverified IPs:** 26 | **Unverified hashes:** 5 (3 SHA-256 + 2 MD5)

## Purpose

Defensive blocking repository for AMOS (Atomic macOS Stealer) infrastructure IOCs, updated daily via automated snapshot runs.

## Blocklist Files

| File | Contents | Firewall-safe? |
|------|----------|----------------|
| `blocklists/domains.txt` | Verified C2/delivery domains, one per line | **YES** |
| `blocklists/ips.txt` | Verified C2 IP addresses, one per line | **YES** |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only) | Review before use |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets only) | Review before use |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without additional review.**

## Raw Blocklist URLs

- Domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Snapshots

Daily full reports are in `snapshots/YYYY-MM-DD.md`. The latest snapshot is always mirrored to `latest.md`.

## IOC Classification

- **verified** — indicator appeared in the body of a successfully fetched vendor report
- **unverified** ⚠️ — indicator sourced only from a search-result snippet or a report whose fetch was blocked; never placed in `blocklists/domains.txt` or `blocklists/ips.txt`

## Sources

Primary verified source: Microsoft Security Blog (2026-05-06, 2026-08-05).  
Additional intelligence from: Unit 42, Cyera, Ransom-ISAC, Darktrace, Moonlock, Trend Micro, Jamf Threat Labs, CloudSEK, SANS ISC (search snippets; most blocked by egress policy).
