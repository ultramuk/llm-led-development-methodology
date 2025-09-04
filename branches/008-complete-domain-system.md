# BRANCH-008: 내 도메인 LLM 시스템 완성

## 실습 목표

fruit를 템플릿으로 활용하여 자신의 도메인에 특화된 완전한 LLM 시스템을 구축한다.

## 참고 원리

- 모든 ROOT 원칙들의 통합 적용
- fruit 시스템의 실제 구현체 참고

## 예상 결과물

완성된 도메인별 LLM 시스템:

```text
my-domain-system/
├── system-prompt.md         # 최종 시스템 프롬프트
├── agents/                  # 완성된 에이전트 세트
│   ├── [domain-1]/
│   ├── [domain-2]/
│   └── meta/
├── commands/                # 완성된 커맨드 세트
│   ├── [workflow-1]/
│   ├── [workflow-2]/
│   └── quality/
└── documents/               # 완성된 문서 체계
    ├── templates/
    ├── guidelines/
    ├── design/
    └── discussions/
```

## 필요한 지식

- 1-7 BRANCH의 모든 내용
- fruit 시스템의 전체 구조
- 자신의 도메인 전문성

## 실습 과정

1. **시스템 통합 점검**
   - 목적: 1-7 BRANCH 결과물 통합
   - 결과물: 일관된 전체 시스템
   - 요구조건: 모든 구성요소가 연동
   - 검증기준: 충돌 없는 통합

2. **도메인 특화 완성**
   - 목적: 내 분야에 최적화
   - 결과물: 도메인별 전문 구성요소
   - 요구조건: fruit 예시를 뛰어넘는 전문성
   - 검증기준: 실무 적용 가능

3. **실전 테스트**
   - 목적: 실제 프로젝트에 적용
   - 결과물: 사용 사례와 결과
   - 요구조건: 최소 1주간 실사용
   - 검증기준: 생산성 향상 확인

4. **시스템 최적화**
   - 목적: 사용 경험을 바탕으로 개선
   - 결과물: 최적화된 최종 시스템
   - 요구조건: 피드백 반영
   - 검증기준: 효율성과 편의성

5. **문서화 완성**
   - 목적: 시스템 사용법과 유지보수 가이드
   - 결과물: README와 사용자 가이드
   - 요구조건: 다른 사람도 사용 가능
   - 검증기준: 독립적 시스템 구축 가능

## 도메인별 예시

**🎮 게임 개발:**

- agents/gameplay/, agents/graphics/
- commands/build-scene/, commands/optimize/
- documents에 게임 디자인 문서

**📊 데이터 사이언스:**

- agents/analysis/, agents/ml/
- commands/clean-data/, commands/model/
- documents에 데이터 명세서

**🏗️ DevOps/인프라:**

- agents/infrastructure/, agents/monitoring/
- commands/deploy/, commands/rollback/
- documents에 인프라 아키텍처

**💼 비즈니스/기획:**

- agents/strategy/, agents/analysis/
- commands/report/, commands/plan/
- documents에 비즈니스 요구사항

## 검증 방법

- [ ] fruit와 동등한 수준의 완성도인가?
- [ ] 내 도메인에 특화된 전문성이 있는가?
- [ ] 1-7 BRANCH의 모든 요소가 통합되었는가?
- [ ] 실제 프로젝트에서 사용 가능한가?
- [ ] 다른 사람에게 공유/전수 가능한가?

## 예상 난이도

상급 - 전체 시스템 통합과 도메인 전문성

## 선택적 도전 과제

- 오픈소스 템플릿 공개
- 커뮤니티와 경험 공유
- 새로운 도메인 확장
- 팀 표준 시스템 구축
