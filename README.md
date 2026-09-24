# AMOS / Atomic macOS Stealer — IOC Blocklists

**Last updated:** 2026-09-24 UTC  
**Verified domains:** 143 | **Verified IPs:** 9 | **Unverified domains:** 7 | **Unverified IPs:** 4 | **SHA-256 hashes:** 5

Daily snapshots of indicators of compromise (IOCs) explicitly attributed to AMOS (Atomic macOS Stealer) and its direct variants, collected for defensive blocking purposes.

## Files

| File | Description |
|------|-------------|
| `latest.md` | Full current report (Korean, defanged) |
| `snapshots/YYYY-MM-DD.md` | Historical daily snapshots |
| `blocklists/domains.txt` | **VERIFIED** domains only — safe to feed directly into a firewall/DNS sinkhole |
| `blocklists/ips.txt` | **VERIFIED** IPs only — safe to feed directly into a firewall |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only, fetch blocked) — review before blocking |
| `blocklists/unverified-ips.txt` | Unverified IPs — review before blocking |

> **Important:** `blocklists/domains.txt` and `blocklists/ips.txt` are the **only** files safe to feed directly into a firewall or DNS sinkhole. All other blocklist files require manual review before operational use.

## Raw blocklist URLs

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Methodology

- IOCs are cumulative — entries are never dropped unless a fetched report explicitly confirms sinkhole or takedown.
- Every IOC is classified as **verified** (appeared in a successfully fetched report body) or **unverified** (search snippet or fetch-blocked source only).
- Only verified IOCs appear in `blocklists/domains.txt` and `blocklists/ips.txt`.
- All IOC mentions in reports use defanged notation (`example[.]com`, `1.2.3[.]4`); blocklist files use raw un-defanged values.
- Reports are written in Korean per project convention.
