# AMOS IOC Repository

**Last updated:** 2026-11-26 UTC

| Category | Count |
|---|---|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 39 |
| Unverified IPs | 26 |
| Unverified hashes (SHA-256) | 3 |
| Unverified hashes (MD5) | 2 |

## Blocklist files

| File | Description |
|---|---|
| `blocklists/domains.txt` | **VERIFIED** domains — safe to feed directly into a firewall/DNS sinkhole |
| `blocklists/ips.txt` | **VERIFIED** IPs — safe to feed directly into a firewall |
| `blocklists/unverified-domains.txt` | Unverified domains — review before blocking |
| `blocklists/unverified-ips.txt` | Unverified IPs — review before blocking |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole without additional review.**

## Raw blocklist URLs

- Verified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- Verified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

## Snapshots

Daily full reports are in `snapshots/YYYY-MM-DD.md`. The most recent snapshot is always at `latest.md`.

## Notes

- IOCs are cumulative; entries are only removed when a successfully-fetched source in the same run explicitly reports them sinkholed or taken down.
- Unverified IOCs come from search result snippets or reports that could not be fetched.
- All blocklist files are un-defanged (no `[.]` substitution), one entry per line, sorted and deduplicated.
- AMOS infrastructure rotates quickly; behavioral detections are more durable than domain/IP blocklists.
