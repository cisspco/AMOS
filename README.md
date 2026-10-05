# AMOS IOC Repository

**Last updated:** 2026-10-05 UTC (automated daily snapshot)

## Counts
| Category | Count |
|---|---|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 14 |
| Unverified IPs | 9 |
| **Total verified IOCs** | **162** |
| **Total unverified IOCs** | **23** |

## Blocklist Files

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only verified IOCs drawn from successfully fetched vendor reports. The unverified files (`unverified-domains.txt`, `unverified-ips.txt`) require additional confirmation before operational use.

| File | Description | Raw URL |
|---|---|---|
| `blocklists/domains.txt` | Verified AMOS C2/delivery domains | [raw](blocklists/domains.txt) |
| `blocklists/ips.txt` | Verified AMOS C2 IPs | [raw](blocklists/ips.txt) |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only) | [raw](blocklists/unverified-domains.txt) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets only) | [raw](blocklists/unverified-ips.txt) |

## Snapshots

Daily full reports are in `snapshots/YYYY-MM-DD.md`. The most recent snapshot is always at `latest.md`.

## Sources

Primary verified sources (successfully fetched):
- [Microsoft Security Blog — ClickFix macOS utilities campaign](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/) — 2026-05-06
- [Microsoft Security Blog — macOS ClickFix cloaked gates](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/) — 2026-08-05

Additional sources tracked (proxy-blocked, unverified):
- Darktrace AMOS investigation (2026-10)
- Unit42 AMOS stealer activity (2026)
- Trend Micro OpenClaw campaign (2026)
- Moonlock AMOS AI agent mimicry (2026)
- Hunt.io Atomic Stealer tracking (2026)
- Sophos AMOS analysis (2026)

## About

This repository tracks Atomic macOS Stealer (AMOS) infrastructure for defensive blocking purposes. All IOCs are attributed to AMOS or confirmed direct variants. IOCs are never silently promoted from unverified to verified status — promotion requires a successfully fetched vendor report.
