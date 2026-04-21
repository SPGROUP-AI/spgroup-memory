# JARVIS 메모리
Last Updated: 2026-04-21

## 역할
SPGROUP 이메일 인텔리전스 AI — jarvis@spgpinc.com 계정 자동화 운영

## 핵심 설정
- 실행 계정: jarvis@spgpinc.com
- 알림 대상: brianlee@spgpinc.com
- Claude 모델: claude-sonnet-4-5
- Sheets ID: 1gQ2VOsA2Eo7eUdgShj9BxpnWGj99QddpG5rV2ltmDGk
- Apps Script ID: 1xSrT_3Qq9cylEEguiQi9a362VNMqzbQEWXD7kdqvKAO6-8EliTI6VxZA

## 이메일 분류 기준 (가먼트 수출)
ORDER / SAMPLE / SHIPMENT / PAYMENT / COMPLAINT / PRICE / NEW_BUYER / INTERNAL / OTHER

## 우선순위 기준
- URGENT: 클레임/결제분쟁/선적긴급 → 즉시
- HIGH: PO확인/샘플승인/인보이스 → 오늘 내
- NORMAL: 일반 업무 → 이번 주
- LOW: FYI/뉴스레터

## AutoReply 규칙
- [SPGROUP INQUIRY] 태그 이메일만 자동 답장
- var INQUIRY_TAG = '[SPGROUP INQUIRY]'; (함수 내부 선언 필수)
- 발신자 자동 답장 + brianlee@ 알림

## Daily Report
- 매일 월~토 09:00 KST → brianlee@spgpinc.com
- Gmail 직접 검색 (Sheets 파싱 우회)
- brianlee@ 발신/답장 제외
- 클릭 → Gmail 스레드 이동
- UTF-8 한글 정상

## 알려진 버그 수정 이력
- parseEmail msgId 스코프 → 함수 내부 선언
- isAlreadyProcessed 타임아웃 → 라벨 기반 경량화
- KST 날짜 형식 버그 → 수정
- INQUIRY_TAG 전역 const → 함수 내부 var

## 세션 노트
- 2026.04.21: v4.0 완료, Daily 33건, GitHub Memory 구축
- MEMORY PROTOCOL 에이전트 지침 추가 시작 (HUNTER 완료)
