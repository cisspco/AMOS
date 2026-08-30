# AMOS / Atomic macOS Stealer — IOC Tracker

**마지막 업데이트 (Last Updated):** 2026-08-30 UTC

## 현재 IOC 집계
| 종류 | 검증됨 | 미검증 |
|------|--------|--------|
| 도메인 | 146 | 1 |
| IP | 10 | 0 |
| SHA-256 해시 | 4 | 0 |

## 블록리스트 다운로드 (Raw URLs)

> ⚠️ **`blocklists/domains.txt` 및 `blocklists/ips.txt`만 방화벽/DNS 싱크홀에 직접 투입하기에 안전합니다.**
> `unverified-*` 파일은 검색 스니펫 출처 IOC로 오탐 위험이 있으며 검토 후 사용하십시오.

- **검증된 도메인:** `blocklists/domains.txt`
- **검증된 IP:** `blocklists/ips.txt`
- **미검증 도메인:** `blocklists/unverified-domains.txt`
- **미검증 IP:** `blocklists/unverified-ips.txt`

## 스냅샷
- 최신 전체 보고서: [`latest.md`](latest.md)
- 일별 아카이브: [`snapshots/`](snapshots/)

## 소개
이 저장소는 AMOS(Atomic macOS Stealer) 및 직접 연관 변종의 활성 C2 인프라를 방어적 차단 목적으로 매일 자동 수집합니다.
IOC는 공개된 벤더 보고서에서 추출하며, 검증된 IOC(직접 페치 성공)와 미검증 IOC(검색 스니펫 출처)를 분리 관리합니다.
