Customer Inquiry Operations Automation

n8n 기반 고객 문의 처리 자동화 포트폴리오 프로젝트입니다.

고객 문의를 입력받아 데이터를 정리하고 검증한 뒤, 문의 유형을 분류하고 AI로 답변 초안을 생성합니다. 이후 사람의 승인 여부에 따라 처리 상태를 결정하고 결과를 Data Table에 기록합니다.

Workflow

Customer Inquiry Form
→ Normalize Input
→ Validate Required Fields
→ Validate Email Format
→ Classify Inquiry Type
→ Generate AI Draft Response
→ Human Approval
→ Save Processing Result

Main Features
고객 문의 Form 입력
입력 데이터 정규화
필수값 검증
이메일 형식 검증
가격 / 기술 / 환불 / 기타 문의 분류
AI 기반 답변 초안 생성
Human-in-the-loop 승인 구조
승인 / 거절 상태 처리
처리 결과 Data Table 기록
오류 처리 Workflow 구현
Tech Stack
n8n
JavaScript Expressions
LLM API
n8n Data Tables
Git / GitHub
Development Status

Core workflow implemented and tested locally.

Error handling has been implemented but requires additional end-to-end validation.