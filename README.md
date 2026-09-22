# AMOS / Atomic macOS Stealer — IOC Tracker

**Last updated:** 2026-09-22 UTC

| Category | Count |
|---|---|
| Verified domains | 143 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 7 |
| Unverified IPs | 4 |
| **Total verified IOCs** | **157** |
| **Total unverified IOCs** | **11** |

## Blocklist files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These files contain verified IOCs only — defanged in reports, raw (un-defanged) here, one entry per line.

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | **VERIFIED** AMOS C2/delivery domains — firewall/DNS safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | **VERIFIED** AMOS C2 IPs — firewall safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets / blocked fetches) — review before use |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — review before use |

## Raw blocklist URLs (for automation)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Snapshots

Daily snapshots (Korean, defanged) are in [`snapshots/`](snapshots/). [`latest.md`](latest.md) always mirrors the most recent snapshot.

## Methodology

- IOCs are included only when explicitly attributed to AMOS / Atomic Stealer (or confirmed direct variants).
- **Verified**: appeared in the body of a successfully fetched vendor report.
- **Unverified** (⚠️): sourced only from a search-result snippet or a report whose fetch was blocked.
- Blocklists are cumulative. An entry is removed only when a successfully fetched source explicitly reports it sinkholed or taken down.
- IOCs that appear in both lists are a bug — an entry promoted from unverified to verified is removed from the unverified file.

## Primary sources

- Microsoft Security Blog (multiple reports, 2026-02 through 2026-08)
- Unit 42 / Palo Alto Networks (blocked by egress proxy)
- malware.news (blocked by egress proxy)
- IRU blog (blocked by egress proxy)
- CloudSEK (blocked by egress proxy)
