# JARVIS 메모리
Last Updated: 2026-04-22

## 역할
SPGROUP 이메일 인텔리전스 AI — jarvis@spgpinc.com 계정 자동화 운영

## 핵심 설정
- 실행 계정: jarvis@spgpinc.com
- 알림 대상: brianlee@spgpinc.com
- Claude 모델: claude-sonnet-4-5
- Sheets ID: 1gQ2VOsA2Eo7eUdgShj9BxpnWGj99QddpG5rV2ltmDGk
- Apps Script ID: 1xSrT_3Qq9cylEEguiQi9a362VNMqzbQEWXD7kdqvKAO6-8EliTI6VxZA

## 알림 기준 (2026-04-22 변경)
- URGENT만 즉시 Brian 알림
- HIGH/NORMAL/LOW → Daily Report에서 확인 (알림 없음)

## 이메일 분류 (가먼트 수출)
ORDER / SAMPLE / SHIPMENT / PAYMENT / COMPLAINT / PRICE / NEW_BUYER / INTERNAL / OTHER

## 우선순위 기준
- URGENT: 클레임/결제분쟁/선적긴급/신규대형바이어 → 즉시 알림
- HIGH: PO확인/샘플승인/인보이스 → Daily에서 확인
- NORMAL: 일반 업무
- LOW: FYI/뉴스레터

## AutoReply
- [SPGROUP INQUIRY] 태그만 자동 답장
- var INQUIRY_TAG = '[SPGROUP INQUIRY]'; (함수 내부 선언 필수)

## Daily Report
- 매일 월~토 09:00 KST → brianlee@
- Gmail 직접 검색 / UTF-8 / 클릭 → Gmail 링크
- brianlee@ 발신 제외

## GitHub Memory 자동 업데이트
- updateGitHubMemory() — 매주 월 08:00 자동 실행
- updateMemoryNow() — 수동 즉시 실행 가능
- 8개 파일 자동 커밋 (에이전트 5개 + 공통 3개)
- Sheets 최근 7일 이메일 통계 포함

## 세션 노트
- 2026.04.21: v4.0 배포, Daily 33건, GitHub Memory 구축
- 2026.04.22: URGENT만 알림, Memory 자동 업데이트 시스템 완성
