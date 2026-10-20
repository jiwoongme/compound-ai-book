---
description: 
---

# Publish Chapter Workflow
사용자가 `/publish` 명령을 실행하면 다음 절차를 순서대로 터미널에서 실행하고 결과를 보고하라:
1. `quarto render --to html`을 실행하여 웹 페이지 빌드 오류가 없는지 검증한다.
2. `quarto render --to docx`를 실행하여 출판사 제출용 워드 파일이 정상 생성되는지 확인한다.
3. `git status`를 확인하고 변경된 파일과 `_freeze/` 디렉토리를 포함하여 의미 있는 커밋 메시지로 `git commit` 및 `git push origin main`을 수행한다.