# AMOS IOC Snapshot — 2026-08-22 UTC

## 활성 C2 도메인 (23)
- applefilevault[.]com — ClickFix 전달 페이지, AMOS/MacSync 페이로드 배포 (Microsoft, 2026-08-05)
- apricotfilepoint[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- bananafastfile[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- clearl[.]co — OpenClaw 캠페인, AMOS 페이로드 전달 도메인 (Trend Micro, 2026-02/03)
- cloudfilebridge[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- cloudsendhub[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- codex-tips[.]com — AMOS 피싱 루어/전달 도메인, 개발자 문서 사이트 위장 (Brinztech, 2026-08)
- filecedarwallet[.]online — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- filecopperbasket[.]sbs — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- filecrimsonsignal[.]online — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- filemarblegarden[.]sbs — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- fileoceanhammer[.]sbs — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- filerubyfolder[.]sbs — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- filevelvettractor[.]sbs — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- getmacouscloud[.]com — AMOS ClickFix 배포 페이지, 터미널 명령 실행 유도 (SANS ISC, 2026-08-02)
- grove-89[.]com — AMOS 관련 인프라 도메인 (SANS ISC, 2026-08-02)
- lemonfilewave[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- limefilescope[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- macostruecloud[.]xyz — AMOS 관련 인프라 도메인 (SANS ISC, 2026-08-02)
- mangocloudfile[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- orangesmartfile[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)
- render65[.]com — AMOS 로더 리디렉션 도메인 (SANS ISC, 2026-08-02)
- syncdatavault[.]com — ClickFix 전달 페이지, AMOS 페이로드 배포 (Microsoft, 2026-08-05)

## 활성 C2 IP (3)
- 45.94.47[.]149 — ASN57043 Hostkey B.V., AMOS C2 서버, TCP 80 포트 /api/tasks/ 엔드포인트 (SANS ISC/Darktrace, 2026)
- 92.246.136[.]14 — AMOS 2차 하드코딩 C2, 주요 도메인 장애 시 폴백 IP (SANS ISC, 2026)
- 188.166.78[.]138 — AMOS C2 서버, /api/metrics/run 엔드포인트, HTTP POST 데이터 유출 (SANS ISC, 2026-08-02)

## 파일 해시 (0)
### SHA-256
없음

### MD5
없음

## 지속성 아티팩트 (호스트 IOC)
- /tmp/helper — AMOS 페이로드 스테이징 경로 (임시 실행 디렉터리)
- ~/Library/LaunchAgents/ — AMOS 백도어 변형 LaunchAgent plist 지속성 위치
- /var/folders/ — AMOS 임시 페이로드 실행 경로 (일반 패턴)

## 최근 캠페인 요약
- **ClickFix 은닉형 macOS 캠페인 (2026-08-05 보고)**: Microsoft가 추적한 캠페인. 브라우저 핑거프린팅(WebGL GPU 탐지, 숨겨진 mode:"php" 필드)으로 분석 환경을 식별하고 일반 사용자에게만 ClickFix 루어를 노출. 17개 이상의 file<단어><단어> 패턴 도메인 사용. AMOS 및 MacSync 인포스틸러 배포. /curl/<id> URL 패턴으로 원격 AppleScript 실행.
- **AMOS getmacouscloud 캠페인 (2026-08-02 보고)**: SANS ISC가 2026-07-31 랩 감염에서 포착. getmacouscloud[.]com이 "macOS toolkit" 설치를 가장한 터미널 명령 실행을 유도. C2 188.166.78[.]138으로 ZIP 압축 데이터 HTTP POST 전송.
- **AMOS OpenClaw 캠페인 (2026-02/03 보고)**: Trend Micro 보고. OpenClaw AI 어시스턴트 위장, clearl[.]co를 통해 AMOS 페이로드 배포, 92.246.136[.]14를 보조 C2로 사용.
- **AMOS codex-tips 캠페인 (2026-08 보고)**: Brinztech 경보. codex-tips[.]com을 통해 개발자 문서 사이트로 위장하여 AMOS 배포. 환경 분석 방지 기능 및 안티-VM 체크 포함.

## 이번 실행 변경사항
- 신규: 도메인 23개, IP 3개 (최초 실행)
- 제거: 없음

## 차단 운영 포맷 (복붙용)

### Domain blocklist (un-defanged, one per line)
```
applefilevault.com
apricotfilepoint.com
bananafastfile.com
clearl.co
cloudfilebridge.com
cloudsendhub.com
codex-tips.com
filecedarwallet.online
filecopperbasket.sbs
filecrimsonsignal.online
filemarblegarden.sbs
fileoceanhammer.sbs
filerubyfolder.sbs
filevelvettractor.sbs
getmacouscloud.com
grove-89.com
lemonfilewave.com
limefilescope.com
macostruecloud.xyz
mangocloudfile.com
orangesmartfile.com
render65.com
syncdatavault.com
```

### IP blocklist (un-defanged, one per line)
```
45.94.47.149
92.246.136.14
188.166.78.138
```

## 출처
- [Atomic MacOS (AMOS) stealer infection — SANS ISC](https://isc.sans.edu/diary/33208) — 2026-08-02
- [From open lures to cloaked gates: macOS ClickFix campaign — Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2026/08/05/macos-clickfix-campaign-learned-hide/) — 2026-08-05
- [New AMOS Campaign Deploys codex-tips.com Phishing Lures — Brinztech](https://www.brinztech.com/breach-alerts/brinztech-alert-new-atomic-macos-stealer-amos-campaign-deploys-codex-tips-com-phishing-lures-and-anti-analysis-environment-checks) — 2026-08
- [Malicious OpenClaw Skills Used to Distribute Atomic MacOS Stealer — Trend Micro](https://www.trendmicro.com/en_us/research/26/b/openclaw-skills-used-to-distribute-atomic-macos-stealer.html) — 2026-02/03
- [Atomic Stealer (AMOS) Returns: ClickFix, Trojanized Crypto Apps — IRU](https://www.iru.com/blog/atomic-stealer-amos-returns) — 2026
