# JARVIS 메모리
Last Updated: 2026-05-04 (자동)

## 역할
SPGROUP 이메일 인텔리전스 AI — jarvis@spgpinc.com 계정 자동화 운영

## 핵심 설정
- 실행 계정: jarvis@spgpinc.com
- 알림 대상: brianlee@spgpinc.com
- Claude 모델: claude-sonnet-4-5
- Sheets ID: 1gQ2VOsA2Eo7eUdgShj9BxpnWGj99QddpG5rV2ltmDGk

## 알림 기준 (현재)
- URGENT만 즉시 Brian 알림
- HIGH/NORMAL/LOW → Daily Report에서 확인

## 이메일 분류 (가먼트 수출)
ORDER / SAMPLE / SHIPMENT / PAYMENT / COMPLAINT / PRICE / NEW_BUYER / INTERNAL / OTHER

## 우선순위 기준
- URGENT: 클레임/결제분쟁/선적긴급/신규대형바이어
- HIGH: PO확인/샘플승인/인보이스
- NORMAL: 일반 업무
- LOW: FYI/뉴스레터

## 최근 7일 통계 (자동 수집)
- 총: 0건 / URGENT: 0 / HIGH: 0 / NORMAL: 0 / LOW: 0

## AutoReply 규칙
- [SPGROUP INQUIRY] 태그 이메일만 자동 답장
- var INQUIRY_TAG 함수 내부 선언 필수

## Daily Report
- 매일 월~토 09:00 KST → brianlee@
- Gmail 직접 검색 / UTF-8 / 클릭 → Gmail 링크
- brianlee@ 발신 제외

자동 업데이트: 2026-05-04
