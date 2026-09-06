# AMOS / Atomic macOS Stealer — IOC Blocklists

**Last updated:** 2026-09-06 UTC  
**Verified domains:** 140 | **Verified IPs:** 8 | **Unverified domains:** 7 | **Unverified IPs:** 2 | **Hashes (SHA-256):** 4

> ⚠️ `blocklists/domains.txt` and `blocklists/ips.txt` are the **only files safe to feed directly into a firewall or DNS sinkhole**. They contain verified IOCs only, un-defanged, one per line.

## Blocklist URLs (raw)

| File | Contents |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2 domains (firewall-safe) |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs (firewall-safe) |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (review before blocking) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (review before blocking) |

## Latest Snapshot

See [`latest.md`](latest.md) for the full daily report (Korean, defanged IOCs, campaign summaries, source list).

Snapshots are archived under [`snapshots/`](snapshots/).

## Source basis

Primary verified source: Microsoft Security Blog reports (2026-05-06 and 2026-08-05).  
Unverified entries sourced from search snippets only — not confirmed by a directly fetched report.

## Notes

- All IOCs are cumulative. Entries are only removed when a source fetched in the same run explicitly reports sinkhole or takedown.
- An IOC appears in either verified or unverified lists, never both.
- The proxy egress environment blocks most vendor domains (moonlock.com, hunt.io, sophos.com, darktrace.com, brinztech.com, etc.); Microsoft Security Blog is the consistently reachable source.
