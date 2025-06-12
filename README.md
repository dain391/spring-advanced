# SpringAdvanced
## 개발 프로세스
### 1. 요구사항 정의

- 프로젝트 목표 및 주요 기능 도출
- 사용자 시나리오 및 기대 효과 정의

## 기능 설계
### 1. 필수 기능 가이드
<details>
  <summary>Level 1</summary>

- 코드 개선
    - `Early Return` 적용하여 불필요한 로직 실행 방지
    - 불필요한 `if-else` 구조 제거로 가독성 향상
    - DTO에서 유효성 검증 처리로 코드 단순화 및 안정성 확보
- 테스트 코드 작성 및 리팩토링
    - 정상 동작 테스트 케이스 작성
    - 예외 처리 테스트 케이스 작성 및 수정
- 기타 Level 1 필수 개선사항 적용
</details>


<details>
  <summary>Level 2</summary>

- `N+1` 문제 해결
    - `JPQL fetch join` → `@EntityGraph` 기반 리팩토링
- 성능 최적화 및 코드 유지보수성 향상
</details>


<details>
  <summary>Level 3</summary>

- 테스트 코드 심화
    - 예외 처리 테스트 케이스 완성 및 수정
    - 서비스 로직 개선에 따른 테스트 코드 동기화
</details>

### 2. 도전 기능 가이드