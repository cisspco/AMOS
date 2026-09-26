# AMOS / Atomic macOS Stealer — Defensive IOC Repository

**Last updated:** 2026-09-26 UTC  
**Verified domains:** 143 | **Verified IPs:** 9 | **Verified hashes (SHA-256):** 5  
**Unverified domains:** 7 | **Unverified IPs:** 4

> ⚠️ **`blocklists/domains.txt` and `blocklists/ips.txt` are the ONLY files safe to feed directly into a firewall or DNS sinkhole.** They contain exclusively VERIFIED indicators explicitly attributed to AMOS/Atomic Stealer in successfully fetched vendor reports.

---

## Raw blocklist URLs (GitHub raw)

| File | Contents |
|------|----------|
| [`blocklists/domains.txt`](blocklists/domains.txt) | Verified C2/delivery domains — firewall-ready |
| [`blocklists/ips.txt`](blocklists/ips.txt) | Verified C2 IPs — firewall-ready |
| [`blocklists/unverified-domains.txt`](blocklists/unverified-domains.txt) | Unverified domains (search snippets / blocked fetches) |
| [`blocklists/unverified-ips.txt`](blocklists/unverified-ips.txt) | Unverified IPs (search snippets / blocked fetches) |
| [`latest.md`](latest.md) | Full IOC snapshot — most recent run |

---

## Snapshots

Daily snapshots are stored in [`snapshots/`](snapshots/). Each file is named `YYYY-MM-DD.md`.

---

## IOC classification

- **Verified** — indicator appeared in the body of a successfully fetched vendor report explicitly attributing it to AMOS/Atomic Stealer.
- **Unverified** ⚠️ — indicator sourced only from a search-result snippet, or from a report whose fetch was blocked. Do NOT add to production blocklists without independent confirmation.

---

## Primary sources (fetched successfully across all runs)

- [From open lures to cloaked gates: How a macOS ClickFix campaign learned to hide](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/) — Microsoft, 2026-08-05
- [ClickFix campaign uses fake macOS utilities lures to deliver infostealers](https://www.microsoft.com/en-us/security/blog/2026/05/06/clickfix-campaign-uses-fake-macos-utilities-lures-deliver-infostealers/) — Microsoft, 2026-05-06
- [Infostealers without borders: macOS, Python stealers, and platform abuse](https://www.microsoft.com/en-us/security/blog/2026/02/02/infostealers-without-borders-macos-python-stealers-and-platform-abuse/) — Microsoft, 2026-02-02
