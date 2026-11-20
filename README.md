# AMOS IOC Repository

**Last updated:** 2026-11-20 UTC

| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 35 |
| IPs | 9 | 26 |
| SHA-256 hashes | 5 | 3 |
| MD5 hashes | 0 | 2 |

## Blocklist URLs (raw, for firewall/DNS sinkhole import)

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only IOCs verified from successfully fetched vendor reports. The `unverified-*.txt` files should be reviewed manually before blocking.

- `blocklists/domains.txt` — verified domains, un-defanged, sorted
- `blocklists/ips.txt` — verified IPs, un-defanged, sorted
- `blocklists/unverified-domains.txt` — unverified domains (search snippets / blocked fetches)
- `blocklists/unverified-ips.txt` — unverified IPs (search snippets / blocked fetches)

## Daily snapshots

Snapshots are written to `snapshots/YYYY-MM-DD.md` and mirrored to `latest.md`.

## Notes

- IOCs are attributed to AMOS / Atomic macOS Stealer or directly linked variants (Odyssey).
- **Verified** = indicator appeared in the body of a successfully fetched vendor report.
- **Unverified** = indicator came only from a search-result snippet or a report whose fetch was blocked.
- An unverified IOC is never placed in `blocklists/domains.txt` or `blocklists/ips.txt`.
- AMOS infrastructure rotates rapidly; treat older entries as lower confidence.
- Primary verified sources: Microsoft Security Blog (2026-05-06, 2026-08-05).
