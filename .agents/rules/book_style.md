---
trigger: always_on
---

# Book & Tech Blog Writing Rules
1. 모든 `.qmd` 원고 작성 시 반드시 학술 논문이나 공식 기술 문서 출처를 명시할 것.
2. 각 챕터 본문에는 다음 4가지 콜아웃 박스를 적극 활용할 것:
   - `::: {.callout-note title="DS Bridge: 기존 ML 개념과 1:1 매칭하기"}`
   - `::: {.callout-tip title="Architecture Blueprint"}` (Mermaid 다이어그램 포함)
   - `::: {.callout-warning title="Eval Lab & Failure Log"}`
   - `::: {.callout-important title="Production Checklist"}`
3. 파이썬 코드는 Python 3.11+ 타입 힌트(Type Hints)와 Pydantic 스키마를 준수할 것.