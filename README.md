# AMOS IOC Repository

**Last updated:** 2026-10-09 UTC

## Counts
| Category | Count |
|---|---|
| Verified domains | 148 |
| Verified IPs | 9 |
| Verified SHA-256 hashes | 5 |
| Unverified domains | 18 |
| Unverified IPs | 12 |
| Unverified SHA-256 hashes | 3 |

## Blocklist URLs (raw, GitHub)

> ⚠️ `blocklists/domains.txt` and `blocklists/ips.txt` are the **only** files safe to feed directly into a firewall or DNS sinkhole. All other blocklist files contain unverified indicators and must be reviewed before operational use.

- `blocklists/domains.txt` — verified domains, sorted, deduped, un-defanged
- `blocklists/ips.txt` — verified IPs, sorted, deduped, un-defanged
- `blocklists/unverified-domains.txt` — unverified domains (review before use)
- `blocklists/unverified-ips.txt` — unverified IPs (review before use)

## Snapshots

Daily full snapshots are in `snapshots/YYYY-MM-DD.md`. The most recent snapshot is always mirrored to `latest.md`.

## Evidence Levels

- **verified** — IOC appeared in the body of a successfully fetched vendor report
- **unverified** ⚠️ — IOC sourced only from a search-result snippet or from a report whose fetch was blocked

## Recent Activity

AMOS (Atomic macOS Stealer) remains highly active in October 2026. Key ongoing campaigns:
- **Claude Code impersonation (2026-10-02):** Malicious ads posing as Claude Code delivering AMOS via ClickFix Terminal paste trick.
- **macOS ClickFix fingerprinting campaign (2026-08+):** 1,650+ compromised WordPress sites, 154 rotating C2 hostnames, server-side fingerprint gating to evade analysis.
- **Spectrum-themed ClickFix (Russian operators):** panel-spectrum[.]net, homebrewrp[.]com, brewory[.]com infrastructure.
- **Report-URI loader chain (~2026-09-25):** ganalytics-tracker-js injection pattern, AS210644 Aeza staging (45.150.33[.]128), telemetry at 95.163.153[.]80:8133/api/t.

## Notes

- Verified blocklists are **cumulative** — entries are only removed when a fetched report explicitly reports sinkholing or takedown.
- IOC infrastructure rotates frequently; behavioral/path-based detections are more durable than static domain/IP lists.
- Primary verified source: [Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/)
