# SPGROUP — 전체 시스템 컨텍스트
Last Updated: 2026-04-21

## 회사 정보
- **회사명**: SP GROUP CO., LTD (주식회사 에스피그룹)
- **업종**: 가먼트(의류) 수출 벤더 — 해외 바이어에게 의류 제품 수출
- **운영 시장**: KR / US
- **설립**: 2022.12
- **홈페이지**: https://spgpinc.com

## 핵심 연락처
- **Brian Lee** (Director): brianlee@spgpinc.com
- **JARVIS** (AI 이메일 인텔리전스): jarvis@spgpinc.com

## JARVIS 시스템
- Apps Script 프로젝트: jarvis@spgpinc.com 계정
- Google Sheets DB: 1gQ2VOsA2Eo7eUdgShj9BxpnWGj99QddpG5rV2ltmDGk
- GitHub Website: SPGROUP-AI/spgroup-website
- GitHub Memory: SPGROUP-AI/spgroup-memory
- AutoReply 태그: [SPGROUP INQUIRY]

## 트리거 (5개)
| 함수 | 주기 |
|------|------|
| onNewEmailReceived | 5분마다 |
| checkAndAutoReply | 5분마다 |
| generateDailyReport | 매일 09:00 (월~토) |
| checkUnrepliedEmails | 매일 14:00 |
| generateWeeklyReport | 매주 월 08:00 |

## 이메일 분류 (가먼트 수출)
ORDER / SAMPLE / SHIPMENT / PAYMENT / COMPLAINT / PRICE / NEW_BUYER / INTERNAL / OTHER

## VERA 컬러 시스템
Midnight #1A1F2E / SP Blue #2D4FC4 / Periwinkle #6B8CFF
SP Taupe #9B8B72 / Warm Grey #E8E4DD / Chalk #FAFAF8

## 에이전트 팀
| 에이전트 | 역할 | memory 파일 |
|---------|------|------------|
| JARVIS | 이메일 인텔리전스 + AutoReply | agents/jarvis_memory.md |
| HUNTER | US 영업 인텔리전스 | agents/hunter_memory.md |
| APEX | CFO · 재무전략 | agents/apex_memory.md |
| VERA | 디자인 & 문서 | agents/vera_memory.md |
| LUMINA | 웹사이트 관리 | agents/lumina_memory.md |
