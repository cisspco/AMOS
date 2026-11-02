# AMOS / Atomic macOS Stealer — IOC Tracker

**Last updated:** 2026-11-02 UTC  
**Verified domains:** 148 | **Verified IPs:** 9 | **Verified SHA-256:** 5  
**Unverified domains:** 27 | **Unverified IPs:** 20 | **Unverified SHA-256:** 3  

Defensive blocking resource for AMOS (Atomic macOS Stealer) and direct variants (Odyssey).
Daily snapshots are committed automatically. All IOCs sourced from public threat-intelligence reports.

## Blocklist files (safe for firewall/DNS sinkhole — VERIFIED only)

> **Only `blocklists/domains.txt` and `blocklists/ips.txt` are safe to feed directly into a firewall or DNS sinkhole.**
> The `unverified-*` files contain indicators sourced only from search-result snippets or blocked fetches and require analyst review before operational use.

| File | Contents | Firewall-safe? |
|------|----------|---------------|
| `blocklists/domains.txt` | 148 verified AMOS C2/delivery domains | YES |
| `blocklists/ips.txt` | 9 verified AMOS C2 IPs | YES |
| `blocklists/unverified-domains.txt` | 27 unverified domains (snippet-only) | NO — analyst review required |
| `blocklists/unverified-ips.txt` | 20 unverified IPs (snippet-only) | NO — analyst review required |

## Raw blocklist URLs (GitHub)

```
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/ips.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-domains.txt
https://raw.githubusercontent.com/cisspco/AMOS/main/blocklists/unverified-ips.txt
```

## Latest full snapshot

See [latest.md](latest.md) for today's full IOC report with defanged indicators, campaign summaries, and source attribution.

## Evidence levels

- **verified** — indicator appeared in the body of a successfully fetched vendor report
- **unverified** ⚠️ — indicator came only from a search-result snippet, or from a report whose fetch was blocked

## Network note

This tracker runs in a cloud sandbox with restricted egress. Vendor domains (Unit 42, Ransom-ISAC, Moonlock, Trend Micro, Broadcom, etc.) are currently outside the session's allowed network domains (EGRESS_BLOCKED). To promote unverified IOCs to verified status, allow those domains in the session's network policy.
