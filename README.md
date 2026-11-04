# AMOS IOC Repository

**Last updated:** 2026-11-04 UTC

## Counts
| List | Count |
|------|-------|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 29 |
| Unverified IPs | 21 |
| Unverified SHA-256 hashes | 3 |
| Unverified MD5 hashes | 2 |

## ⚠️ Blocklist Safety Note

**Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole** — they contain only verified indicators confirmed by successfully fetched vendor reports.

The `unverified-domains.txt` and `unverified-ips.txt` files contain indicators sourced only from search-result snippets or reports that were blocked by egress policy; treat them as leads requiring independent verification before operational use.

## Blocklist URLs (raw, for firewall import)

| File | Purpose |
|------|---------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2 domains — firewall/DNS safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IPs — firewall safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains — research use only |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — research use only |

## Daily Snapshots

Full dated snapshots with Korean-language analysis, campaign summaries, and change tracking are in [`snapshots/`](snapshots/). The latest snapshot is always mirrored to [`latest.md`](latest.md).

## Methodology

- IOCs are classified **verified** only when they appear in the body of a successfully fetched vendor report.
- IOCs sourced only from search-result snippets or egress-blocked reports are classified **unverified** and kept in separate files.
- All four blocklist files are cumulative; entries are never dropped unless a fetched source explicitly reports sinkhole or takedown.
- Indicators are defanged in the report (`example[.]com`, `1.2.3[.]4`); blocklist files contain raw un-defanged values.

## Egress Notes

The following vendor domains have been consistently blocked by the session's network egress policy and have never been successfully fetched. If access is granted, IOCs from these sources may be promoted from unverified to verified on the next run:

- unit42.paloaltonetworks.com
- ransom-isac.org
- www.cloudsek.com
- www.trendmicro.com
- www.darktrace.com
- www.sophos.com
- moonlock.com
- blog.report-uri.com
- aviatrix.ai
- www.iru.com
