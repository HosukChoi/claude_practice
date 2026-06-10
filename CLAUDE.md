# Project Overview

Git과 GitHub 실습 프로젝트입니다.

## 파일 구성

- `README.md` — 유일하게 사용되는 파일. 모든 실습 내용은 이 파일에 작성합니다.
- `docs/Commit_convention.md` — 커밋 컨벤션 문서.

## 작업 지침

- 이 프로젝트에서 새 파일을 생성하지 않습니다. `README.md`만 사용합니다.
- Git 커밋, 브랜치, PR 등 GitHub 관련 작업에 집중합니다.

## 커밋 규칙

커밋 메시지 작성 시 반드시 [docs/Commit_convention.md](docs/Commit_convention.md)의 규칙을 따릅니다.

핵심 규칙 요약:
- type은 대괄호로 감쌈: `[feat]`, `[fix]`, `[docs]` 등
- 형식: `[type]: subject`
- subject는 50자 이내, 명령형, 끝에 마침표 금지
- body가 필요한 경우 무엇을, 왜 변경했는지 작성
- footer에 반드시 `Author: hsw.choi darkchsq@naver.com` 포함
- Claude가 작성에 참여한 경우 `Co-Authored-By: Claude Sonnet 4.6 <noreply@anthropic.com>` 추가
