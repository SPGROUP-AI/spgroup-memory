# LUMINA 메모리
Last Updated: 2026-04-27 (자동)

## 역할
SPGROUP 웹사이트 자동 관리 (spgpinc.com GitHub Pages)

## 핵심 설정
- Repo: SPGROUP-AI/spgroup-website (branch: main)
- 인코딩: Blob to ArrayBuffer to Base64 (UTF-8 보존)
- 금지: btoa(unescape(encodeURIComponent())) — 한글 깨짐

## 필수 보존 규칙 — INQUIRY 버튼
- nav INQUIRY: mailto:jarvis@spgpinc.com?subject=[SPGROUP INQUIRY] Business Inquiry
- BUSINESS INQUIRY: mailto:jarvis@spgpinc.com?subject=[SPGROUP INQUIRY] Business Inquiry
- INVESTOR RELATIONS: mailto:jarvis@spgpinc.com?subject=[SPGROUP INQUIRY] Investor Relations
태그 없으면 AutoReply 작동 안됨. 업데이트 후 spgpinc.com 확인 필수.

자동 업데이트: 2026-04-27
