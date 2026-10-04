# AMOS / Atomic macOS Stealer IOC Repository

**Last updated:** 2026-10-04 UTC  
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified hashes (SHA-256):** 5  
**Unverified domains:** 14 | **Unverified IPs:** 9

This repository tracks indicators of compromise (IOCs) for **AMOS (Atomic macOS Stealer)** and
closely-linked variants (e.g. Odyssey) for defensive blocking purposes.
It is updated daily by an automated scheduled task.

---

## Blocklist files (firewall / DNS sinkhole ready)

> ⚠️ **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a
> firewall or DNS sinkhole.** These contain only *verified* IOCs — indicators that appeared in the
> body of a successfully fetched vendor report. All entries are un-defanged, one per line, sorted
> and deduplicated.

| File | Contents | Safe for firewall? |
|------|----------|--------------------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2 / delivery domains | ✅ Yes |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IP addresses | ✅ Yes |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets only) | ⚠️ Review first |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets only) | ⚠️ Review first |

Raw blocklist URLs (for direct import):
- `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`

---

## Latest snapshot

See [`latest.md`](latest.md) for today's full report, or browse [`snapshots/`](snapshots/) for
historical daily snapshots.

---

## Evidence levels

- **verified** — IOC appeared in the body of a report fetched successfully in the collection run
- **unverified** (⚠️) — IOC came only from a search-result snippet or from a report whose fetch
  was blocked by the egress proxy; treat with caution before blocking in production

---

## Sources (primary)

| Report | Date | Status |
|--------|------|--------|
| [ClickFix campaign uses fake macOS utilities lures to deliver infostealers](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/) | 2026-05-06 | fetched |
| [From open lures to cloaked gates: How a macOS ClickFix campaign learned to hide](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/) | 2026-08-05 | fetched |
| [Atomic Stealer: Darktrace's Investigation of a Growing macOS Threat](https://www.darktrace.com/blog/atomic-stealer-darktraces-investigation-of-a-growing-macos-threat) | 2026-10 | blocked |
| [Atomic Stealer (AMOS) Returns: ClickFix, Trojanized Crypto Apps, and a New macOS Persistence Mechanism](https://www.iru.com/blog/atomic-stealer-amos-returns) | 2026 | blocked |
