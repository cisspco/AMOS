# AMOS IOC Tracker

**Last updated:** 2026-08-24 UTC

| Category | Count |
|---|---|
| Verified domains | 53 |
| Verified IPs | 8 |
| Verified hashes (SHA-256) | 4 |
| Unverified domains | 1 |
| Unverified IPs | 0 |

## Blocklist URLs (raw, for firewall/DNS sinkhole import)

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole — they contain verified IOCs only, un-defanged, one per line.**

- [blocklists/domains.txt](blocklists/domains.txt) — 53 verified AMOS C2/delivery domains
- [blocklists/ips.txt](blocklists/ips.txt) — 8 verified AMOS C2/exfiltration IPs
- [blocklists/unverified-domains.txt](blocklists/unverified-domains.txt) — 1 unverified domain (search-snippet only; do NOT use in production blocklists without independent verification)
- [blocklists/unverified-ips.txt](blocklists/unverified-ips.txt) — 0 unverified IPs

## Latest Snapshot

See [latest.md](latest.md) for today's full report, or browse [snapshots/](snapshots/) for historical runs.

## Notes

- All blocklist files are **cumulative**: entries are only removed when a successfully fetched report explicitly reports sinkholing or takedown.
- IOCs sourced only from search-result snippets or blocked fetch attempts are kept in `unverified-*` files and are never promoted to the production blocklists without confirmation.
- Hashes are tracked in snapshot reports only; no hash blocklist file is maintained (hashes rotate too quickly for a stable blocklist).
