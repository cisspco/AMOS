# AMOS / Atomic macOS Stealer — IOC Blocklist Repository

**Last updated:** 2026-11-15 UTC

## Counts

| List | Count |
|------|-------|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 34 |
| Unverified IPs | 26 |
| Unverified SHA-256 hashes | 3 |
| Unverified MD5 hashes | 2 |

## Blocklist files

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These files contain only IOCs verified from successfully fetched vendor reports. The `unverified-*` files are for research review only.

| File | Description | Raw URL |
|------|-------------|---------|
| `blocklists/domains.txt` | Verified domains — firewall-safe | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt |
| `blocklists/ips.txt` | Verified IPs — firewall-safe | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt |
| `blocklists/unverified-domains.txt` | Unverified domains (research only) | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt |
| `blocklists/unverified-ips.txt` | Unverified IPs (research only) | https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt |

## Snapshots

Daily full reports are in `snapshots/<YYYY-MM-DD>.md`. The latest snapshot is always mirrored to `latest.md`.

## Sources

Verified IOCs sourced from:
- [Microsoft Security Blog — Aug 5, 2026](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/)
- [Microsoft Security Blog — May 6, 2026](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/)
- Microsoft Defender Experts — Feb 2, 2026 (alli-ai campaign)

Unverified IOCs referenced from (fetch blocked in this environment): Cyera (Nov 2026), Unit 42 (Aug/Sep 2026), Ransom-ISAC, Moonlock, Darktrace, CloudSEK, Brinztech, Jamf Threat Labs, infostealers.com, and others — see individual snapshot files for details.

## Notes

- All entries are cumulative; IOCs are removed only when a successfully fetched source explicitly reports sinkholing or takedown.
- IOC defanging (`example[.]com`) is used in Markdown reports; blocklist `.txt` files are un-defanged for direct import.
- This repository is maintained for defensive blocking purposes only.
