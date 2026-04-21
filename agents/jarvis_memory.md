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
- ORDER: PO, 발주서
- SAMPLE: 샘플, MM, 사이즈 스펙
- SHIPMENT: 선적, B/L, 패킹리스트
- PAYMENT: 인보이스, T/T, LC
- COMPLAINT: 클레임, QC 불량
- PRICE: 견적, 단가
- NEW_BUYER: 신규 바이어
- INTERNAL / OTHER

## 우선순위
- URGENT: 클레임/결제분쟁/선적긴급 → 즉시
- HIGH: PO확인/샘플승인/인보이스 → 오늘 내
- NORMAL: 일반 업무 → 이번 주
- LOW: FYI/뉴스레터

## AutoReply 규칙
- 제목에 [SPGROUP INQUIRY] 태그 있을 때만 자동 답장
- 발신자에게 수신확인 HTML 이메일 발송
- brianlee@에게 알림

## Daily Report
- 매일 월~토 09:00 KST 자동 발송
- Gmail 직접 검색으로 수집 (Sheets 파싱 우회)
- brianlee@ 발신/답장 이메일 제외
- 각 이메일 클릭 시 Gmail 스레드로 이동

## 세션 노트
- 2026.04.21: v4.0 배포 완료, 모든 버그 수정, Daily Report 정상 작동
