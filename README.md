# AMOS / Atomic macOS Stealer — IOC Repository

**Last updated:** 2026-08-29 UTC (automated daily snapshot)

## Counts
| Category | Count |
|---|---|
| Verified domains | 146 |
| Verified IPs | 10 |
| Unverified domains | 1 |
| Unverified IPs | 0 |
| SHA-256 hashes | 4 |

## Blocklist Files

> ⚠️ **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.** They contain verified IOCs only, un-defanged, one per line.

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | **Verified** AMOS C2/delivery domains — firewall/sinkhole ready |
| [`blocklists/ips.txt`](blocklists/ips.txt) | **Verified** AMOS C2 IPs — firewall ready |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search-snippet only) — review before blocking |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — review before blocking |

## Raw Blocklist URLs (for automated import)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
```

## Latest Snapshot

Full daily report with campaign context, persistence artifacts, and source attribution:
- [`latest.md`](latest.md) — most recent snapshot
- [`snapshots/`](snapshots/) — full daily history

## Coverage

Tracks **AMOS (Atomic macOS Stealer)** and directly attributed variants only. Sources include Microsoft Security Blog, SANS ISC, Trend Micro, IRU, Darktrace, Brinztech, and active C2 trackers.

All IOCs are defanged in report text; blocklist files contain raw un-defanged values for operational use.
