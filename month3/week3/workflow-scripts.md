```markdown
# Month 3 Week 3 – Workflow Scripts
 
반복 업무에 대한 프롬프트 체인(Workflow Script)을 정리합니다.
 
---
 
## Workflow 1 – [업무 이름 예: 주간 퍼포먼스 리포트]
 
### 1. 개요
 
- 주기: [예: 매주 월요일]  
- 입력 데이터: [예: 채널별 매출/비용/ROI 표 + 주요 메모]
 
### 2. Step & Prompt Chain
 
- Step 1 – Raw Data 요약 (Gemini)
  - Prompt: [내용]
  - 출력 기대: [요약/표 등]
 
- Step 2 – 인사이트 도출 (Claude)
  - Prompt: [내용]
  - 출력 기대: [인사이트 bullet 5개]
 
- Step 3 – 외부 벤치마크 비교 (Perplexity)
  - Prompt: [내용]
  - 출력 기대: [벤치마크/트렌드 요약]
 
- Step 4 – 보고서/PPT 생성 (Copilot)
  - Prompt: [내용]
  - 출력 기대: [2~3페이지 보고서 또는 5~7장 슬라이드]
 
### 3. 실행 시 주의 사항 / 개선 메모
 
- [내용 작성]
```
