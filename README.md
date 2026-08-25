# AMOS IOC Repository

**Last updated:** 2026-08-25 UTC
**Verified domains:** 53 | **Verified IPs:** 8 | **Unverified domains:** 1 | **Unverified IPs:** 0 | **Hashes:** 4 SHA-256

Tracks active infrastructure for AMOS (Atomic macOS Stealer) for defensive blocking. Updated daily by automated snapshot.

## Blocklist files (raw, firewall-ready)

> `blocklists/domains.txt` and `blocklists/ips.txt` are the **only files safe to feed directly into a firewall or DNS sinkhole**. They contain verified-only, un-defanged entries, one per line, suitable for direct import.

| File | Contents |
|------|----------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2/delivery domains (un-defanged) |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IPs (un-defanged) |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains — review before blocking |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — review before blocking |

## Raw blocklist URLs (for direct firewall import)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
```

## Latest snapshot

See [`latest.md`](latest.md) for the most recent full IOC snapshot with context and sources.

Historical snapshots are in the [`snapshots/`](snapshots/) directory.

## Evidence classification

- **Verified**: IOC appeared in the body of a successfully fetched vendor report
- **Unverified** ⚠️: IOC sourced only from a search snippet or from a blocked/unavailable report — do not feed into production blocklists without further vetting
