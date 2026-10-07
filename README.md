# AMOS / Atomic macOS Stealer — Defensive IOC Repository

**Last updated:** 2026-10-07 UTC

## Counts
| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 14 |
| IPs | 9 | 9 |
| SHA-256 hashes | 5 | 3 |
| **Total** | **162** | **26** |

## Blocklist URLs (raw, suitable for firewall/DNS import)

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.** They contain verified IOCs only, un-defanged, one entry per line, sorted and deduplicated.

| File | Contents |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains — firewall-ready |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs — firewall-ready |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (snippet-sourced only) — review before blocking |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (snippet-sourced only) — review before blocking |

## Latest Snapshot

See [`latest.md`](latest.md) for the full daily report including campaign summaries, file hashes, persistence artifacts, and source attributions.

Historical snapshots are in [`snapshots/`](snapshots/).

## About

IOCs are collected daily via automated web search and vendor report analysis. Only IOCs explicitly attributed to AMOS / Atomic macOS Stealer (or closely linked variants such as Odyssey when explicitly stated) are included. Entries are classified as **verified** (appeared in the body of a successfully fetched report) or **unverified** (sourced only from a search-result snippet or from a report whose fetch was blocked by the egress proxy). Verified and unverified IOCs are never mixed in the same blocklist file.
