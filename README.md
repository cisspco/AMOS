# AMOS IOC Repository

**Last updated:** 2026-11-16 UTC

| Category | Count |
|---|---|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 34 |
| Unverified IPs | 26 |
| Unverified hashes (SHA-256) | 3 |
| Unverified hashes (MD5) | 2 |

## Blocklist URLs (raw, for firewall/DNS sinkhole import)

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain VERIFIED entries only (confirmed in a fetched vendor report). The `unverified-*.txt` files require additional validation before operational use.

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified AMOS C2/delivery domains — firewall-ready |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified AMOS C2 IPs — firewall-ready |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets / blocked fetches) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets / blocked fetches) |

## Daily Snapshots

Full daily reports are in [`snapshots/`](snapshots/). The [`latest.md`](latest.md) file always contains the most recent snapshot.

## About

This repository tracks AMOS (Atomic macOS Stealer) infrastructure for defensive blocking purposes. Updated daily via automated search and vendor report collection. IOCs are classified as **verified** (confirmed in a fetched report body) or **unverified** (from search result snippets or blocked fetches).

AMOS infrastructure rotates rapidly — treat all entries as time-sensitive and cross-reference against current vendor feeds before operational use.
