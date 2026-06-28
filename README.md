# AI Workflow Classroom

AI 워크플로우 수업에서 모든 참여자가 함께 사용하는 공통 실습 저장소입니다.

이 저장소는 최종 팀 프로젝트 저장소가 아닙니다. 수업마다 여러 사람이 같은 GitHub 저장소에서 브랜치, 커밋, PR, 리뷰 흐름을 연습하고, 그 기록을 기수별로 축적하기 위한 공간입니다.

## 기본 흐름

1. 수업 기수 폴더를 확인합니다.
2. 자기 GitHub ID와 사용하는 에이전트가 드러나는 브랜치를 만듭니다.
3. 자기 파일만 수정해 첫 PR을 만듭니다.
4. PR 본문에 AI에게 무엇을 맡겼고 사람이 무엇을 검토했는지 적습니다.
5. PR URL과 작업 맥락은 개인 LLM-Wiki에도 남깁니다.

## 브랜치 이름

```bash
git switch -c 2026-06-ai-workflow/glen15/codex/add-member-note
```

형식:

```text
{cohort}/{github-id}/{agent}/{task}
```

## 파일 위치

첫 PR에서는 아래 파일처럼 자기 파일만 만듭니다.

```text
cohorts/2026-06-ai-workflow/members/{github-id}.md
```

팀 단위 기록이 필요하면 아래 위치를 사용합니다.

```text
cohorts/2026-06-ai-workflow/teams/{team-name}/{github-id}.md
```

## 커밋 메시지

```bash
git commit -m "docs: AI 워크플로우 2026-06 glen15 Codex 실습 기록 추가"
```

## 참고 문서

- [PR 가이드](docs/pr-guide.md)
- [팀 협업 규칙](docs/team-rules.md)

