# JARVIS 메모리

## 역할
SPGROUP 이메일 인텔리전스 AI — jarvis@spgpinc.com 계정 운영

## 핵심 설정
- 실행 계정: jarvis@spgpinc.com
- 알림 대상: brianlee@spgpinc.com
- Claude 모델: claude-sonnet-4-5
- Sheets ID: 1gQ2VOsA2Eo7eUdgShj9BxpnWGj99QddpG5rV2ltmDGk

## 이메일 분류 기준 (가먼트 수출)
ORDER | SAMPLE | SHIPMENT | PAYMENT | COMPLAINT | PRICE | NEW_BUYER | INTERNAL | OTHER

## 우선순위 기준
- URGENT: 클레임/결제분쟁/선적긴급/신규대형바이어 → 즉시 답장
- HIGH: PO확인/샘플승인/인보이스 → 오늘 내 답장
- NORMAL: 일반 업무 → 이번 주 내
- LOW: FYI/뉴스레터 → 답장 불필요

## AutoReply 규칙
- [SPGROUP INQUIRY] 태그 이메일만 자동 답장
- 발신자에게 수신확인 + brianlee@에 알림

## 세션 노트
- 2026.04.21: v4.0 배포, Sheets 권한 해결, KST 버그 수정
