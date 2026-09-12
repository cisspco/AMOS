# AMOS IOC Tracker

**Last updated:** 2026-09-12 UTC

| Category | Count |
|---|---|
| Verified domains | 143 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 7 |
| Unverified IPs | 3 |

## Blocklist files

| File | Contents | Safe for firewall/DNS? |
|---|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2 domains, one per line | **YES** |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IPs, one per line | **YES** |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) | Review before use |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets only) | Review before use |

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** The unverified files are provided for analyst review and should not be used for automated blocking without independent verification.

## Raw blocklist URLs (GitHub)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Latest snapshot

See [`latest.md`](latest.md) for the most recent full IOC report, or browse [`snapshots/`](snapshots/) for historical runs.

## IOC evidence levels

- **Verified** — indicator appeared in the body of a report fetched successfully during that run
- **Unverified** — indicator came only from a search-result snippet, or from a report whose fetch was blocked
