# AMOS / Atomic macOS Stealer — IOC Tracking Repository

**Last updated:** 2026-10-03 UTC (automated daily snapshot)

| Category | Verified | Unverified |
|---|---|---|
| Domains | 148 | 14 |
| IPs | 9 | 9 |
| SHA-256 hashes | 5 | 0 |
| **Total** | **162** | **23** |

## Raw blocklist URLs

| File | Description |
|---|---|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains — safe for firewall/DNS sinkhole |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs — safe for firewall |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains — review before blocking |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs — review before blocking |

> **`blocklists/domains.txt` and `blocklists/ips.txt` are the only files safe to feed directly into a firewall or DNS sinkhole.** The unverified files contain indicators sourced only from search snippets and should be validated before operational use.

## Latest snapshot

[`latest.md`](latest.md) — updated every run with the full Korean-language IOC report (defanged), campaign summaries, and blocklist-ready code blocks.

Historical snapshots are in [`snapshots/`](snapshots/).

## Coverage

This repository tracks **Atomic macOS Stealer (AMOS)** and its direct variants (Odyssey when explicitly linked). Indicators are classified as **verified** (appeared in the body of a successfully fetched vendor report) or **unverified** (search snippet only or fetch-blocked source). Only verified IOCs appear in `blocklists/domains.txt` and `blocklists/ips.txt`.

Primary verified source: Microsoft Security Blog (2026-02-02, 2026-05-06, 2026-08-05).
