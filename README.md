# AMOS / Atomic macOS Stealer — IOC Repository

**Last updated:** 2026-09-03 UTC  
**Verified domains:** 140 | **Verified IPs:** 8 | **Unverified domains:** 7 | **Unverified IPs:** 2 | **Hashes (SHA-256):** 4

This repository contains daily snapshots of indicators of compromise (IOCs) attributed to **AMOS (Atomic macOS Stealer)** and its known variants, maintained for defensive blocking purposes.

## ⚠️ Firewall-safe blocklists

> Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole. They contain **verified** entries only — IOCs confirmed in the body of a successfully fetched vendor report.

| File | Description |
|------|-------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | ✅ **Verified** C2/delivery domains — firewall-safe |
| [`blocklists/ips.txt`](blocklists/ips.txt) | ✅ **Verified** C2 IPs — firewall-safe |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | ⚠️ Unverified domains — search snippets / blocked sources only |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | ⚠️ Unverified IPs — search snippets / blocked sources only |

## Raw blocklist URLs (for scripted import)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Snapshots

Daily full reports are in [`snapshots/`](snapshots/). The latest snapshot is always at [`latest.md`](latest.md).

## Sources (cumulative)

| Report | Date | Status |
|--------|------|--------|
| [Hunting MacSync Stealer infrastructure through behavioral pivots](https://www.microsoft.com/en-us/security/blog/2026/08/18/hunting-macsync-stealer-infrastructure-through-behavioral-pivots/) | 2026-08-18 | fetched (MacSync only) |
| [From open lures to cloaked gates: macOS ClickFix campaign learned to hide](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/) | 2026-08-05 | fetched ✅ |
| [ClickFix campaign uses fake macOS utilities lures to deliver infostealers](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/) | 2026-05-06 | fetched ✅ |
| [Atomic macOS (AMOS) stealer infection — SANS ISC](https://isc.sans.edu/diary/33208/) | 2026-07-31 est. | blocked ❌ |
| [Atomic Stealer (AMOS) Returns — IRU](https://www.iru.com/blog/atomic-stealer-amos-returns) | unknown | blocked ❌ |
| [ATOMIC Stealer: macOS Credential Theft — Hunt.io](https://hunt.io/malware-families/atomic-stealer) | unknown | blocked ❌ |
| [Malicious OpenClaw Skills — Trend Micro](https://www.trendmicro.com/en_us/research/26/b/openclaw-skills-used-to-distribute-atomic-macos-stealer.html) | 2026-02/03 | blocked ❌ |

## Methodology

- IOCs are included only when **explicitly attributed** to AMOS / Atomic Stealer (or confirmed direct variants).
- Blocklists are **cumulative** — entries are never removed unless a successfully fetched report in that run confirms sinkhole or takedown.
- Unverified IOCs (search snippets or blocked sources) are kept separately and never placed in firewall-safe lists.
- All data is defanged in narrative; blocklist files contain un-defanged values for direct operational use.
