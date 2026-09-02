# AMOS / Atomic macOS Stealer IOC Repository

**Last updated:** 2026-09-02 UTC (automated daily snapshot)

## Counts
| Category | Count |
|---|---|
| Verified domains | 140 |
| Verified IPs | 8 |
| Verified SHA-256 hashes | 4 |
| Unverified domains | 7 |
| Unverified IPs | 2 |

## Blocklist Files

> **IMPORTANT:** Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole. These files contain **verified-only** entries drawn from successfully fetched threat intelligence reports. The `unverified-*` files are for analyst review only.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | **Verified** AMOS C2 domains — firewall/DNS safe | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt) |
| `blocklists/ips.txt` | **Verified** AMOS C2 IPs — firewall safe | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets / blocked fetches) | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets / blocked fetches) | [raw](https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt) |

## Snapshots

Daily snapshots are stored in `snapshots/YYYY-MM-DD.md`. The `latest.md` file always reflects the most recent run.

## Evidence Levels

- **Verified** — IOC appeared in the body of a successfully fetched vendor report
- **Unverified** ⚠️ — IOC came only from a search-result snippet or a report whose fetch was blocked

IOCs observed in a report dated within the last 7 days are marked 🔥.

## Sources (most recent verified fetches)
- Microsoft Security Blog, 2026-08-05: [From open lures to cloaked gates: How a macOS ClickFix campaign learned to hide](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/)
- Microsoft Security Blog, 2026-05-06: [ClickFix campaign uses fake macOS utilities lures to deliver infostealers](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/)
