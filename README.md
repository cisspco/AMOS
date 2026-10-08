# AMOS IOC Tracker

**Last updated:** 2026-10-08 UTC  
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified SHA-256 hashes:** 5  
**Unverified domains:** 14 | **Unverified IPs:** 10 | **Unverified SHA-256 hashes:** 3

Automated daily snapshot of Atomic macOS Stealer (AMOS) indicators of compromise for defensive blocking purposes.

## Blocklist files

| File | Contents | Safe for firewall/DNS sinkhole? |
|------|----------|--------------------------------|
| `blocklists/domains.txt` | Verified AMOS domains, un-defanged, sorted | **YES** |
| `blocklists/ips.txt` | Verified AMOS IPs, un-defanged, sorted | **YES** |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets / blocked fetches) | NO — review before use |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets / blocked fetches) | NO — review before use |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.** All entries are sourced from successfully fetched vendor reports and explicitly attributed to AMOS/Atomic Stealer.

## Raw blocklist URLs

- Verified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- Verified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Snapshots

Daily snapshots are stored in `snapshots/YYYY-MM-DD.md`. The most recent snapshot is always mirrored as `latest.md`.

## IOC classification

- **verified** — indicator appeared in the body of a successfully fetched vendor report
- **unverified** ⚠️ — indicator came only from a search-result snippet or a report whose fetch was blocked; confirm before blocking

## Key campaigns tracked

- **2026-10-02** Claude Code impersonation AMOS campaign (ClickFix, Odyssey variant) — unverified
- **2026-08-05** ClickFix gate-cloaking campaign (Microsoft analysis) — verified
- **2026-07-28+** WordPress compromise ClickFix AMOS campaign (Ransom-ISAC) — partially unverified
- **2026-05-06** Loader/Script/Helper triple campaign (Microsoft analysis) — verified
- **2026-02-02** alli-ai fake AI tool AMOS campaign (Microsoft analysis) — verified
- **2026-02** ClawHavoc / ClawHub AI marketplace campaign — unverified
