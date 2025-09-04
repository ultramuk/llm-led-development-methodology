# BRANCH-002: 문서 구조 구축

## 실습 목표

fruit의 documents 구조를 참고하여 프로젝트 문서 체계를 구축한다.

## 참고 원리

- ROOT-004: 명시적으로 컨텍스트 관리를 하라
- ROOT-005: 구조를 통해 역할을 명확하게 하라

## 예상 결과물

documents 폴더 구조:
```text
my-system/
└── documents/
    ├── templates/      # 재사용 템플릿 (fruit 참고)
    ├── guidelines/     # 코딩 표준, 규칙
    ├── design/         # 요구사항, 기획
    └── discussions/    # 의사결정 기록
```

## 필요한 지식

- 문서 분류 체계
- 프로젝트 정보 구조화
- 마크다운 문서 작성

## 실습 과정

1. **documents 폴더 생성**
   - 목적: 외부 컨텍스트 관리 체계
   - 결과물: 4개 하위 폴더
   - 요구조건: fruit 구조 참고
   - 검증기준: 역할이 명확히 구분

2. **templates 폴더 구성**
   - 목적: 재사용 가능한 템플릿
   - 결과물: task-template.md 등
   - 요구조건: 실제 사용할 템플릿
   - 검증기준: 반복 작업에 활용

3. **guidelines 문서 작성**
   - 목적: 프로젝트 표준 정의
   - 결과물: coding-standards.md
   - 요구조건: 명확하고 측정 가능
   - 검증기준: LLM이 규칙 준수

4. **design 폴더 활용**
   - 목적: Human의 요구사항 관리
   - 결과물: requirements.md
   - 요구조건: Why와 What 중심
   - 검증기준: How는 포함하지 않음

5. **PROJECT.md 작성**
   - 목적: 프로젝트 핵심 정보
   - 결과물: documents/PROJECT.md
   - 요구조건: 5분 내 이해 가능
   - 검증기준: 신규 참여자 테스트

## 검증 방법

- [ ] fruit/documents와 유사한 구조인가?
- [ ] 각 폴더의 역할이 명확한가?
- [ ] PROJECT.md가 프로젝트를 잘 설명하는가?
- [ ] 템플릿이 재사용 가능한가?
- [ ] LLM이 문서를 활용하는가?

## 예상 난이도

초급 - 구조 생성과 기본 문서 작성

## 선택적 도전 과제

- architectures 폴더 추가
- process 폴더로 워크플로우 관리
- 문서 간 상호참조 체계 구축