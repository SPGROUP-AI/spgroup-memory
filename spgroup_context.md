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
- Apps Script ID: 1xSrT_3Qq9cylEEguiQi9a362VNMqzbQEWXD7kdqvKAO6-8EliTI6VxZA
- Google Sheets DB: 1gQ2VOsA2Eo7eUdgShj9BxpnWGj99QddpG5rV2ltmDGk
- GitHub Website: SPGROUP-AI/spgroup-website
- GitHub Memory: SPGROUP-AI/spgroup-memory
- AutoReply 태그: [SPGROUP INQUIRY]
- Claude 모델: claude-sonnet-4-5

## 트리거 5개 (jarvis@spgpinc.com)
| 함수 | 주기 | 상태 |
|------|------|------|
| onNewEmailReceived | 5분마다 | 가동 |
| checkAndAutoReply | 5분마다 | 가동 |
| generateDailyReport | 매일 09:00 (월~토) | 가동 |
| checkUnrepliedEmails | 매일 14:00 | 가동 |
| generateWeeklyReport | 매주 월 08:00 | 가동 |

## 이메일 분류 (가먼트 수출)
ORDER / SAMPLE / SHIPMENT / PAYMENT / COMPLAINT / PRICE / NEW_BUYER / INTERNAL / OTHER

## VERA 컬러 시스템
Midnight #1A1F2E / SP Blue #2D4FC4 / Periwinkle #6B8CFF
SP Taupe #9B8B72 / Warm Grey #E8E4DD / Chalk #FAFAF8

## 에이전트 팀
| 에이전트 | 역할 | 상태 | memory |
|---------|------|------|--------|
| JARVIS | 이메일 인텔리전스 + AutoReply | 자동화 가동 | agents/jarvis_memory.md |
| HUNTER | US 영업 인텔리전스 | 대화형 | agents/hunter_memory.md |
| APEX | CFO · 재무전략 | 대화형 | agents/apex_memory.md |
| VERA | 디자인 & 문서 | 대화형 | agents/vera_memory.md |
| LUMINA | 웹사이트 관리 | 자동화 가동 | agents/lumina_memory.md |

## Phase 현황
- Phase 1 완료: JARVIS 이메일 인텔리전스 완전 가동
- Phase 2 진행: 에이전트 고도화 + GitHub Memory 연동
- Phase 3 예정: HUNTER 영업 자동화
- Phase 4 예정: APEX 재무 인텔리전스
- Phase 5 예정: 에이전트 간 협업 자동화
