# AMOS / Atomic macOS Stealer IOC Repository

**Last updated:** 2026-11-09 UTC  
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified SHA-256:** 5  
**Unverified domains:** 32 | **Unverified IPs:** 23 | **Unverified hashes:** 5 (3 SHA-256 + 2 MD5)

Defensive IOC tracking for AMOS (Atomic macOS Stealer) and direct variants (Odyssey).  
Updated daily by automated scheduled run. All IOCs are defanged in reports; blocklist files are un-defanged.

## Blocklist files (raw, un-defanged, one entry per line)

| File | Contents | Safe for firewall/DNS? |
|------|----------|------------------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified domains only | **YES** |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified IPs only | **YES** |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) | Review before use |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets only) | Review before use |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without additional review.**  
> Unverified files contain indicators sourced only from search result snippets; they have not been confirmed in a fully-fetched vendor report.

## Latest snapshot

See [`latest.md`](latest.md) for the full current IOC report with context, campaign summaries, and change log.

Historical daily snapshots are in [`snapshots/`](snapshots/).

## Network note

This repository's automated runner operates in a sandboxed cloud environment. Vendor domains (Unit 42, Trend Micro, Broadcom, Ransom-ISAC, Report-URI, etc.) are currently outside the allowed egress list, so all fetches are EGRESS_BLOCKED. All IOCs beyond the initial Microsoft-sourced verified set remain unverified until egress is expanded. To allow a vendor domain, add it to the session's network policy.
