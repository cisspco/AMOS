# AMOS IOC Repository

Defensive blocking intelligence for **AMOS (Atomic macOS Stealer)** and direct variants (Odyssey). Updated daily by automated snapshot runs.

**Last updated:** 2026-11-12 UTC
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified SHA-256:** 5
**Unverified domains:** 32 | **Unverified IPs:** 26 | **Unverified hashes:** 5 (3 SHA-256 + 2 MD5)

---

## Blocklist files

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.** These contain only IOCs verified from successfully fetched vendor reports. The `unverified-*` files are for research review only.

| File | Contents | Safe to block? |
|------|----------|---------------|
| `blocklists/domains.txt` | Verified C2/delivery domains, sorted | ✅ Yes |
| `blocklists/ips.txt` | Verified C2 IPs, sorted | ✅ Yes |
| `blocklists/unverified-domains.txt` | Unverified domains (search snippets only) | ⚠️ Review first |
| `blocklists/unverified-ips.txt` | Unverified IPs (search snippets only) | ⚠️ Review first |

### Raw blocklist URLs (latest commit)
- Domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt`
- IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt`
- Unverified domains: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt`
- Unverified IPs: `https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt`

---

## Snapshots

Daily full reports are in `snapshots/<YYYY-MM-DD>.md`. The latest is always at `latest.md`.

---

## Evidence levels

- **verified** — IOC appeared in the body of a report fetched successfully in that run's Step 2
- **unverified ⚠️** — IOC came only from a search-result snippet, or from a report whose fetch was blocked

IOCs are promoted from unverified → verified when confirmed by a successfully fetched report in a later run, and noted under `승격(미검증→검증)` in that day's snapshot.

---

## Sources tracked

Microsoft Security Blog, Unit 42 (Palo Alto), Trend Micro, Moonlock, Cyera, Mate Security, Broadcom/Symantec, Cato CTRL, ransom-isac.org, blog.report-uri.com, Darktrace, CloudSEK, infostealers.com, SANS ISC, and others. See individual snapshots for full source lists.
