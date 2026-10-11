# AMOS IOC Repository

**Last updated:** 2026-10-11 UTC

Defensive blocking indicators for **AMOS / Atomic macOS Stealer** and known direct variants (Odyssey). Collected daily from vendor reports and threat intelligence feeds.

## Counts (cumulative)

| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 24 |
| IPs | 9 | 15 |
| SHA-256 hashes | 5 | 3 |
| **Total IOCs** | **162** | **42** |

## Blocklist files

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.** They contain only verified indicators explicitly attributed to AMOS in successfully fetched vendor reports. All entries are un-defanged (no `[.]`), one per line, sorted, deduplicated.

| File | Description |
|---|---|
| `blocklists/domains.txt` | VERIFIED C2/delivery domains — firewall-safe |
| `blocklists/ips.txt` | VERIFIED C2 IPs — firewall-safe |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets / blocked fetches) |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets / blocked fetches) |

### Raw blocklist URLs (GitHub)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Daily snapshots

Full Korean-language IOC reports with evidence levels, campaign summaries, and delta tracking are in `snapshots/` and mirrored to `latest.md`.

## Attribution policy

An IOC is **verified** only if it appeared in the body of a successfully fetched vendor report in the run that added it. All other IOCs (search-snippet-only, fetch-blocked sources) are **unverified** and kept in separate files. Verified IOCs are never silently demoted; unverified IOCs are promoted when a later run fetches confirming evidence.
