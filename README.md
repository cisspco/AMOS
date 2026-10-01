# AMOS IOC Tracker

**Last updated:** 2026-10-01 UTC

| Category | Count |
|---|---|
| Verified domains | 143 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 12 |
| Unverified IPs | 7 |

## Blocklist files

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains — safe to feed directly into a firewall or DNS sinkhole |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs — safe to feed directly into a firewall |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search-snippet sources only) — review before blocking |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search-snippet sources only) — review before blocking |

> **Note:** `blocklists/domains.txt` and `blocklists/ips.txt` are the **only** files safe to feed directly into a firewall or DNS sinkhole without manual review.

## Latest snapshot

See [`latest.md`](latest.md) for the most recent full IOC report, or browse [`snapshots/`](snapshots/) for daily history.

## Sources

IOCs are sourced from Microsoft Security Blog, Darktrace, Hunt.io, IRU, Ransom-ISAC, Unit42, and other vendor threat intelligence reports. Only IOCs confirmed in successfully fetched reports are placed in the verified blocklists.
