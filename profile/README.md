# RoleFit

AI 기반 직무 탐색·추천 플랫폼 **롤핏** 개발 조직입니다.

롤핏은 사용자의 이력, 성향, 관심사, 우선순위를 분석해 사용자가 지원할 수 있는 직무와 준비 후 도전 가능한 직무를 구분해주는 커리어 추천 서비스입니다.

## Repositories

| Repository | Purpose | Stack |
| --- | --- | --- |
| [`backend`](https://github.com/JIKMUPICK/backend) | API server, auth, resume analysis, recommendation pipeline | NestJS, TypeScript |
| [`frontend`](https://github.com/JIKMUPICK/frontend) | User-facing web app and product UI | Next.js, React, TypeScript |
| [`.github`](https://github.com/JIKMUPICK/.github) | Organization profile, issue templates, PR template | GitHub community health |

## Product Principles

1. Start from job discovery, not job posting search.
2. Explain every recommendation with evidence.
3. Separate immediately applicable jobs from jobs that require preparation.
4. Keep MVP scope focused: interview, resume analysis, recommendation, report.

## MVP Flow

```text
Landing
→ Onboarding
→ AI job interview
→ Resume upload / text input
→ Resume analysis
→ Priority setting
→ Job candidate comparison
→ RoleFit report
```

## Development Workflow

1. Create or pick a GitHub Issue before coding.
2. Use small PRs scoped to one issue.
3. Include verification evidence in every PR.
4. Keep backend and frontend contracts documented.

## Naming

- Service: 롤핏 / RoleFit
- AI agent: 롤봇
- Report: 롤핏 리포트
- Score: 롤핏 스코어
