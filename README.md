# 올리브영 RMP 모니터링 대시보드 (목업)

올리브영 참여형 네이티브 광고(RMP) BI 이벤트를 시각화한 모니터링 대시보드 목업.

**Live:** https://buzzviltheo.github.io/oy-rmp-monitoring-test/

## 무엇

- 단일 HTML 파일, 정적 사이트 (Tailwind + Chart.js CDN)
- 더미 데이터 기반
- 광고 유형 / 상세 유형(variation) / 캠페인(라인아이템) 필터로 조회

## 측정 항목

- KPI 4종 — 지면 노출 / 진입률 / 참여 완료율 / 광고주 전달 트래픽
- 참여 퍼널 — 5단계 (`section_impression` → `ad_click` → `result_impression` → `reward_button_click` → `reward_complete`)
- 일별 추이 — 노출 · 완료
- 광고 유형별 노출 분포 + 완료율
- OX퀴즈 depth 도달률 / VS형 라운드 도달률
- 맞춤형 동의 전환율 (`ifa_provided`)
- 광고주 페이지 랜딩 유형 분포 (`landing_type`)
- 캠페인 단위 성과 테이블

## BI 이벤트 설계 문서

[\[DATA\] 올리브영 RMP BI 이벤트](https://buzzvil.atlassian.net/wiki/spaces/DEM/pages/5073240427)
