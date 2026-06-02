# Superpowers

[Superpowers](https://github.com/obra/superpowers) is a complete software development methodology for your coding agents, built on top of a set of composable skills and some initial instructions that make sure your agent uses them.

> 이 저장소는 [obra/superpowers](https://github.com/obra/superpowers)의 포크이며, 한국어 스킬 가이드 문서를 추가했습니다.

> 📖 **전체 개념 한눈에 보기 →** [Superpowers Skills 가이드 인덱스](https://deity719.github.io/claude-plugin-superpowers/skill-guides/index.html)

이 플러그인(plugin)은 Claude Code의 개발 워크플로우를 체계화하는 **14개 스킬(skills)** 로 구성됩니다. 각 스킬은 독립적으로 조합할 수 있으며, 아래 카탈로그에서 스킬 이름을 누르면 스킬별 상세 가이드로 이동합니다.

## 스킬 카탈로그 (Skill Catalog)

### 🧭 Process Skills — 접근 방법론 (HOW to approach)

- **[brainstorming](https://deity719.github.io/claude-plugin-superpowers/skill-guides/brainstorming.html)** — 기능·컴포넌트·동작 변경 등 모든 창작 작업 전, 요구사항과 설계 의도를 먼저 탐색한다.
- **[writing-plans](https://deity719.github.io/claude-plugin-superpowers/skill-guides/writing-plans.html)** — 스펙/요구사항을 받아 코드를 만지기 전에 다단계 실행계획을 문서화한다.
- **[executing-plans](https://deity719.github.io/claude-plugin-superpowers/skill-guides/executing-plans.html)** — 작성된 계획을 체크포인트와 함께 단계별로 실행한다.
- **[systematic-debugging](https://deity719.github.io/claude-plugin-superpowers/skill-guides/systematic-debugging.html)** — 버그·테스트 실패·예상 밖 동작을 만나면 수정 전에 증거 기반 4단계 근본 원인 분석을 수행한다.
- **[test-driven-development](https://deity719.github.io/claude-plugin-superpowers/skill-guides/test-driven-development.html)** — Red-Green-Refactor 사이클로 기능을 구현한다.
- **[verification-before-completion](https://deity719.github.io/claude-plugin-superpowers/skill-guides/verification-before-completion.html)** — "완료"를 선언하기 전에 실제 동작 검증 증거를 반드시 확인한다.

### ⚡ Execution Skills — 병렬 실행 및 격리 (Parallel & Isolation)

- **[dispatching-parallel-agents](https://deity719.github.io/claude-plugin-superpowers/skill-guides/dispatching-parallel-agents.html)** — 서로 독립적인 2개 이상의 태스크를 동시에 실행한다.
- **[subagent-driven-development](https://deity719.github.io/claude-plugin-superpowers/skill-guides/subagent-driven-development.html)** — 독립 태스크로 이뤄진 구현 계획을 현재 세션에서 서브에이전트에 위임해 실행한다.
- **[using-git-worktrees](https://deity719.github.io/claude-plugin-superpowers/skill-guides/using-git-worktrees.html)** — git worktree로 격리된 작업 공간에서 피처 작업을 진행한다.

### 🔍 Review & Completion — 리뷰 및 마무리

- **[requesting-code-review](https://deity719.github.io/claude-plugin-superpowers/skill-guides/requesting-code-review.html)** — 기능 완료 후 또는 머지 전에 코드 리뷰를 요청한다.
- **[receiving-code-review](https://deity719.github.io/claude-plugin-superpowers/skill-guides/receiving-code-review.html)** — 리뷰 피드백을 기술적 근거에 따라 반영하거나 응답한다.
- **[finishing-a-development-branch](https://deity719.github.io/claude-plugin-superpowers/skill-guides/finishing-a-development-branch.html)** — 머지·PR·정리 등 개발 브랜치 통합 옵션을 처리한다.

### 🛠 Meta Skills — 메타 스킬

- **[using-superpowers](https://deity719.github.io/claude-plugin-superpowers/skill-guides/using-superpowers.html)** — 대화 시작 시 스킬을 탐색하고 호출하는 규칙을 확립한다.
- **[writing-skills](https://deity719.github.io/claude-plugin-superpowers/skill-guides/writing-skills.html)** — 새 스킬을 작성·검증·배포한다.

## 문서 (Documentation)

- **가이드 인덱스 (전체 개념):** [`docs/skill-guides/index.html`](docs/skill-guides/index.html) · [라이브](https://deity719.github.io/claude-plugin-superpowers/skill-guides/index.html)
- **스킬별 가이드:** `docs/skill-guides/<skill>.html` — 위 카탈로그의 각 링크 참고
- 스킬 소스: `skills/<skill>/SKILL.md`
