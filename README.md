# AMOS IOC Repository

**Last updated:** 2026-10-18 UTC

## Counts
| Category | Count |
|---|---|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 27 |
| Unverified IPs | 15 |
| Unverified SHA-256 hashes | 3 |

## Blocklist Files

| File | Description | Safe for firewall/DNS? |
|---|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2 domains, un-defanged, sorted | **YES** |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs, un-defanged, sorted | **YES** |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) | Review before use |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets only) | Review before use |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without manual review.** All other files contain unverified indicators sourced from search snippets where the primary report could not be fetched due to egress restrictions.

## Raw Blocklist URLs (GitHub raw)

- Verified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- Verified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Latest Full Snapshot

See [`latest.md`](latest.md) for the most recent full IOC report including campaign summaries, persistence artifacts, and source attribution.

## Purpose

This repository tracks **AMOS (Atomic macOS Stealer)** infrastructure for defensive blocking purposes. Updated daily via automated snapshot. IOCs are classified as **verified** (body of a successfully fetched vendor report) or **unverified** (search snippet / blocked fetch only).

## Sources
Primary: Microsoft Security Blog (fetched). Secondary (blocked/snippets): dev.to, Darktrace, Unit 42, ransom-isac.org, CloudSEK, Moonlock, Broadcom, IRU, report-uri.com, cybersecuritynews.com, and others.
