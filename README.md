# multi-agent-performance
### AI Multi-Agent를 활용한 백엔드 성능 병목 분석 및 진단 정확도 비교 실험
1. 에이전트는 어떤 기준으로 역할을 나누어야 할까?

2. 에이전트 사이에서는 어떤 정보를 언제 공유하는 게 좋을까?

3. 역할 분리와 문맥 공유가 정확도·비용·시간에 어떤 영향을 미칠까?

Overview <br>
본 프로젝트는 기존에 개발한 Product API를 대상으로 AI Multi-Agent가 백엔드 시스템의 성능 병목을 어떻게 분석하고 진단하는지 실험하는 프로젝트입니다.<br>
단순히 여러 AI Agent를 실행하는 것을 넘어, 에이전트 간 문맥(Context) 공유 방식이 문제 분석의 정확도에 어떤 영향을 미치는지 검증하는 것을 목표로 합니다. <br>
또한 부하 테스트와 모니터링을 통해 실제 병목 원인을 확인하고, AI가 제안한 개선안이 실제 성능 향상으로 이어지는지 측정하고자 합니다.<br>

Roadmap <br>
기존 Product API 아키텍처 및 코드 분석<br>
성능 병목 후보 선정 및 재현<br>
부하 테스트 환경과 측정 지표 검증<br>
Single Agent 분석 구현<br>
Shared Context Multi-Agent 구현<br>
Isolated Context Multi-Agent 구현<br>
동일 조건에서 진단 정확도 비교<br>
개선안 적용 및 성능 재측정<br>
실험 결과 분석 및 문서화<br>
<br>
Results<br>
실험 진행 후 다음 항목을 기록할 예정입니다.<br>
실험 환경 및 재현 조건<br>
성능 병목의 실제 원인<br>
Agent 구성별 진단 결과 및 정확도<br>
실행 시간과 토큰 사용 비용<br>
개선 전후 TPS, p95/p99, 에러율 비교<br>
실험의 한계 및 후속 개선 방향
