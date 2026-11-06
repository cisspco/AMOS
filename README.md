# AMOS / Atomic macOS Stealer IOC Repository

**Last updated:** 2026-11-06 UTC  
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified SHA-256:** 5  
**Unverified domains:** 32 | **Unverified IPs:** 23 | **Unverified hashes:** 5 (3 SHA-256 + 2 MD5)

This repository tracks indicators of compromise (IOCs) for AMOS (Atomic macOS Stealer) and its known direct variants for defensive blocking purposes. Updated daily by automated snapshot runs.

## Blocklist files

| File | Description | Safe to feed to firewall/DNS sinkhole? |
|------|-------------|----------------------------------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified domains — appeared in body of a successfully fetched report | **YES** |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified IPs — appeared in body of a successfully fetched report | **YES** |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains — search-snippet only or fetch blocked | Review before use |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — search-snippet only or fetch blocked | Review before use |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without additional review.**

## Raw blocklist URLs

- Verified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- Verified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Latest snapshot

See [`latest.md`](latest.md) for the most recent full IOC report with context, campaign summaries, host-based artifacts, and file hashes.

Historical snapshots are stored in [`snapshots/`](snapshots/).

## Notes

- All blocklist `.txt` files are cumulative — entries are only removed when a source fetched in a given run explicitly reports the entry as sinkholed or taken down.
- An IOC is **verified** only when it appeared in the body of a report fetched successfully in that run.
- An IOC is **unverified** when it came only from a search-result snippet or a report whose fetch was blocked.
- Unverified IOCs are promoted to verified (and moved from `unverified-*.txt` to the main lists) when a later run successfully fetches a confirming source.
- IOCs are never silently promoted or placed in verified lists based on search snippets alone.
