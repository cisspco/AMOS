# AMOS / Atomic macOS Stealer — IOC Tracker

**Last updated:** 2026-09-14 UTC  
**Maintained by:** Automated daily snapshot (defensive blocking purposes only)

## Counts

| Category | Verified | Unverified |
|---|---|---|
| Domains | 143 | 7 |
| IPs | 9 | 3 |
| SHA-256 hashes | 5 | 0 |
| **Total IOCs** | **157** | **10** |

## Blocklist files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only verified IOCs explicitly attributed to AMOS/Atomic Stealer in fetched vendor reports. The `unverified-*` files are for analyst review only.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified C2/delivery domains | [domains.txt](blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified C2 IP addresses | [ips.txt](blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (snippet-only attribution) | [unverified-domains.txt](blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (snippet-only attribution) | [unverified-ips.txt](blocklists/unverified-ips.txt) |

## Latest snapshot

See [latest.md](latest.md) for the full current report, or browse [snapshots/](snapshots/) for historical daily reports.

## Sources

Primary verified sources (all Microsoft Security Blog):
- [From open lures to cloaked gates (2026-08-05)](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/)
- [ClickFix campaign uses fake macOS utilities lures (2026-05-06)](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/)
- [Infostealers without borders (2026-02-02)](https://www.microsoft.com/en-us/security/blog/2026/02/02/infostealers-without-borders-macos-python-stealers-and-platform-abuse/)

## Disclaimer

This repository is maintained for **defensive purposes only**. IOCs are sourced exclusively from public vendor threat intelligence reports. All domain/IP entries in verified blocklists have been explicitly attributed to AMOS/Atomic Stealer infrastructure in successfully fetched reports.
