# docs

분석 보고서와 원본 자료를 분리해 둔다.

## 구조

- `reports/` — 분석 보고서 HTML
  - `painpoints.html` — 페인포인트 상위 15개 정리
  - `service-direction.html` — 진입 전략과 1·2·3단계 로드맵
  - `pre-spec-plan.html` — 스펙 작성 전 사전 단계 6주 계획
  - `dev-methodology.html` — tmux 기반 AI 에이전트 회사 운영 방식
- `sources/` — 분석에 사용한 원본 자료
  - `business-plan/` — 사업계획서 PDF 2편
  - `case-studies/` — 실제 손해사정 보고서 사례 PDF 3편 (별첨 1·2·3)

## 운영 규칙

- 새 보고서는 `reports/`에 추가하고 본 README의 목록을 함께 갱신한다.
- 원본 자료(PDF·DOCX 등)는 `sources/` 아래 성격별 하위 폴더에 둔다.
- 보고서 안에서 원본 자료를 참조할 때는 `docs/sources/...` 경로를 그대로 사용한다.
