# AMOS / Atomic macOS Stealer — IOC Tracking Repository

**Last updated:** 2026-11-21 UTC

| Category | Count |
|---|---|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 35 |
| Unverified IPs | 26 |
| Unverified hashes (SHA-256 + MD5) | 5 |

## Purpose

This repository tracks infrastructure IOCs (indicators of compromise) for **AMOS / Atomic macOS Stealer** and known direct variants, for defensive blocking purposes. Snapshots are generated daily by an automated collector.

## Blocklist Files

| File | Contents | Safe for firewall? |
|---|---|---|
| `blocklists/domains.txt` | **Verified** domains, un-defanged, sorted | ✅ YES |
| `blocklists/ips.txt` | **Verified** IPs, un-defanged, sorted | ✅ YES |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only) | ⚠️ Review first |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets only) | ⚠️ Review first |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without additional review.**

### Raw blocklist URLs (GitHub raw)
- `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Evidence Levels

- **Verified** — IOC extracted from the body of a successfully fetched vendor report
- **Unverified ⚠️** — IOC sourced only from a search-result snippet or a report whose fetch was blocked; never placed in the verified blocklists

## Snapshots

Full daily snapshots (Korean, defanged) are in `snapshots/YYYY-MM-DD.md`. The latest snapshot is always `latest.md`.

## Sources

Primary verified sources (successfully fetched at least once):
- Microsoft Security Blog — 2026-05-06 and 2026-08-05 ClickFix/AMOS analyses
- Microsoft Security Blog — 2026-02-02 alli-ai campaign analysis

Blocked sources (DNS not resolved by this environment):
- unit42.paloaltonetworks.com, moonlock.com, cybersecuritynews.com, darktrace.com, ransom-isac.org, pcapai.com
