# AMOS IOC Repository

**Last updated:** 2026-11-27 UTC  
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified SHA-256:** 5  
**Unverified domains:** 39 | **Unverified IPs:** 26 | **Unverified hashes:** 5 (3 SHA-256 + 2 MD5)

## Blocklist Files

| File | Description | Firewall-safe? |
|------|-------------|----------------|
| `blocklists/domains.txt` | Verified AMOS C2/delivery domains (un-defanged, sorted) | YES |
| `blocklists/ips.txt` | Verified AMOS C2 IPs (un-defanged, sorted) | YES |
| `blocklists/unverified-domains.txt` | Unverified/snippet-only domains | Review before use |
| `blocklists/unverified-ips.txt` | Unverified/snippet-only IPs | Review before use |

**`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.** The unverified files contain indicators sourced only from search snippets or blocked reports; treat them as leads requiring further validation.

## Blocklist URLs (raw, for firewall import)

- Verified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- Verified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Snapshots

Daily IOC reports (Korean, defanged) are in `snapshots/`. The most recent snapshot is always at `latest.md`.

## About

This repository tracks Atomic macOS Stealer (AMOS) infrastructure for defensive blocking purposes. All IOCs are sourced from public threat intelligence reports. Blocklists are cumulative — entries are only removed when a source confirms sinkhole or takedown.
