# AMOS IOC Repository

**Last updated:** 2026-11-24 UTC (automated daily snapshot)

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 38 |
| IPs | 9 | 26 |
| SHA-256 hashes | 5 | 3 |
| MD5 hashes | 0 | 2 |
| **Total IOCs** | **162** | **69** |

## Blocklist URLs (raw, for firewall/DNS import)

> **Important:** Only `blocklists/domains.txt` and `blocklists/ips.txt` are verified and safe to feed directly into a firewall or DNS sinkhole. The `unverified-*.txt` files require manual review before operational use.

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | VERIFIED domains — firewall/DNS-safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | VERIFIED IPs — firewall-safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets only) |

## Latest Snapshot

See [`latest.md`](latest.md) for the full current IOC report with context, campaign summaries, and change log, or browse [`snapshots/`](snapshots/) for historical daily runs.

## Methodology

- **Verified** IOCs appeared in the body of a successfully fetched vendor report.
- **Unverified** IOCs came from search result snippets or reports whose fetch was blocked by the egress proxy.
- Blocklists are cumulative; entries are only removed when a fetched report explicitly confirms sinkholing or takedown.
- IOCs are defanged in the markdown reports (`example[.]com`, `1.2.3[.]4`) but un-defanged in the `blocklists/*.txt` files.

## Sources (primary)
- Microsoft Security Blog — https://www.microsoft.com/en-us/security/blog/
- Unit 42 / Palo Alto Networks
- Moonlock / Intego
- Darktrace
- RANSOM-ISAC
- Cyera Threat Research
