# multi-agent-performance
1. 에이전트는 어떤 기준으로 역할을 나누어야 할까?

2. 에이전트 사이에서는 어떤 정보를 언제 공유하는 게 좋을까?

3. 역할 분리와 문맥 공유가 정확도·비용·시간에 어떤 영향을 미칠까?

Roadmap
기존 Product API 아키텍처 및 코드 분석
성능 병목 후보 선정 및 재현
부하 테스트 환경과 측정 지표 검증
Single Agent 분석 구현
Shared Context Multi-Agent 구현
Isolated Context Multi-Agent 구현
동일 조건에서 진단 정확도 비교
개선안 적용 및 성능 재측정
실험 결과 분석 및 문서화

Results
실험 진행 후 다음 항목을 기록할 예정입니다.
실험 환경 및 재현 조건
성능 병목의 실제 원인
Agent 구성별 진단 결과 및 정확도
실행 시간과 토큰 사용 비용
개선 전후 TPS, p95/p99, 에러율 비교
실험의 한계 및 후속 개선 방향
