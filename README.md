# AMOS IOC Repository

**Last updated:** 2026-09-05 UTC

Defensive blocking IOC feed for **AMOS (Atomic macOS Stealer)** and confirmed direct variants, maintained by daily automated snapshot runs.

## Counts (cumulative)
| Category | Verified | Unverified |
|---|---|---|
| Domains | 140 | 7 |
| IPs | 8 | 2 |
| SHA-256 hashes | 4 | 0 |
| **Total** | **152** | **9** |

## Blocklist files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only verified IOCs explicitly attributed to AMOS in successfully fetched vendor reports.

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | ✅ VERIFIED domains — firewall/sinkhole safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | ✅ VERIFIED IPs — firewall safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | ⚠️ Unverified domains (search snippets / blocked sources) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | ⚠️ Unverified IPs (search snippets / blocked sources) |

## Raw blocklist URLs (for scripts / MDM)
```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Latest snapshot
See [`latest.md`](latest.md) for the full daily report including campaign summaries, hashes, persistence artifacts, and fetch/block status.

## Snapshots archive
Daily snapshots are stored in [`snapshots/`](snapshots/).

## Sources policy
- **Verified**: IOC appeared in the body of a report successfully fetched in Step 2 of the daily run
- **Unverified**: IOC came only from a search snippet or a report whose fetch was blocked

IOCs are cumulative. An entry is removed only when a successfully fetched source in the same run explicitly reports it sinkholed or taken down.
