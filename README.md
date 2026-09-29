# AMOS / Atomic macOS Stealer — IOC Tracking Repository

**Last updated:** 2026-09-29 UTC  
**Verified domains:** 143 | **Verified IPs:** 9 | **Verified hashes:** 5  
**Unverified domains:** 8 | **Unverified IPs:** 4  
**Total verified IOCs:** 157 | **Total unverified IOCs:** 12

## Purpose

Daily automated snapshots of known AMOS (Atomic macOS Stealer) indicators of compromise, maintained for defensive blocking purposes.

## Blocklist Files

| File | Contents | Firewall-safe? |
|------|----------|----------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains | **YES** |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IP addresses | **YES** |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (snippet-only) | Use with caution |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (snippet-only) | Use with caution |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.** Unverified lists require human review before operational use.

## Raw Blocklist URLs

- Domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Latest Snapshot

See [`latest.md`](latest.md) for today's full report with all IOC context, campaign summaries, and source attribution.

Historical snapshots are in the [`snapshots/`](snapshots/) directory.

## Evidence Levels

- **Verified** — IOC appeared in the body of a successfully fetched vendor report
- **Unverified** ⚠️ — IOC sourced only from a search snippet or a report whose fetch was blocked

Blocklists are cumulative. An IOC is only removed when a successfully fetched report explicitly confirms it has been sinkholed or taken down.
