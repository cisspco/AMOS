# AMOS IOC Repository

Automated daily snapshots of Atomic macOS Stealer (AMOS) indicators of compromise for defensive blocking.

**Last updated:** 2026-11-05 UTC

## Counts
| List | Count |
|------|-------|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 32 |
| Unverified IPs | 22 |
| Unverified hashes (SHA-256) | 3 |
| Unverified hashes (MD5) | 2 |

## Blocklist URLs (raw, for firewall/DNS import)

> **Important:** Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole. These files contain only verified indicators confirmed from successfully fetched vendor reports. The `unverified-*.txt` files contain indicators sourced only from search snippets or blocked fetches — treat them as leads requiring additional validation before blocking.

- Verified domains: `blocklists/domains.txt`
- Verified IPs: `blocklists/ips.txt`
- Unverified domains (leads only): `blocklists/unverified-domains.txt`
- Unverified IPs (leads only): `blocklists/unverified-ips.txt`

## Snapshots

Daily full reports are in `snapshots/YYYY-MM-DD.md`. The latest is always at `latest.md`.

## Evidence levels

- **verified** — indicator appeared in the body of a report fetched successfully
- **unverified** ⚠️ — indicator sourced only from a search-result snippet or a report whose fetch was blocked

## Sources (primary)

- [ClickFix campaign uses fake macOS utilities lures to deliver infostealers](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/) — Microsoft, 2026-05-06
- [From open lures to cloaked gates: How a macOS ClickFix campaign learned to hide](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/) — Microsoft, 2026-08-05

## Egress-blocked vendor domains (allowlist in session network settings to improve coverage)

The following vendor domains are currently blocked by the session's egress policy. Adding them would improve IOC coverage:

- unit42.paloaltonetworks.com
- ransom-isac.org
- blog.report-uri.com
- www.catonetworks.com
- www.cloudsek.com
- www.trendmicro.com
- www.sophos.com
- moonlock.com
- www.darktrace.com
