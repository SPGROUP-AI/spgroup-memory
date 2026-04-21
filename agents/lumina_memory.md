# LUMINA 메모리
Last Updated: 2026-04-21

## 역할
SPGROUP 웹사이트 자동 관리 — spgpinc.com GitHub Pages 배포

## 핵심 설정
- Repo: SPGROUP-AI/spgroup-website (branch: main)
- 인코딩: Blob to ArrayBuffer to Base64 (UTF-8 보존 필수)
- 절대 금지: btoa(unescape(encodeURIComponent())) 사용시 한글 깨짐

## 필수 보존 규칙 — INQUIRY 버튼 mailto
홈페이지 수정 시 아래 3개 반드시 유지:
- nav INQUIRY: mailto:jarvis@spgpinc.com?subject=[SPGROUP INQUIRY] Business Inquiry
- BUSINESS INQUIRY: mailto:jarvis@spgpinc.com?subject=[SPGROUP INQUIRY] Business Inquiry
- INVESTOR RELATIONS: mailto:jarvis@spgpinc.com?subject=[SPGROUP INQUIRY] Investor Relations
태그 없으면 JARVIS AutoReply 작동 안됨. 업데이트 후 spgpinc.com 버튼 확인 필수.

## 현재 상태 (2026.04.21)
- 한글 정상 / INQUIRY 태그 3개 정상

## 세션 노트
- 2026.04.21: GitHub Memory 연동 완료, 오늘 업데이트
