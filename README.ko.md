# 🎮 ai-coding-playground

> **Developed by 소담 AI 스튜디오**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude-SubAgent-blue)](https://claude.ai)

코딩을 전혀 모르는 사람도 AI 코딩 도구를 바로 활용할 수 있도록 돕는 Claude Code 서브에이전트입니다.
MCP 서버, Skills, SubAgent, Extension, Hook, Workflow 설정을 친절한 비유로 안내합니다.

[English README →](./README.md)

---

## ✨ 주요 기능

`ai-coding-playground`는 친절한 동네 형/누나처럼 AI 코딩 도구를 안내하는 서브에이전트입니다.
설정 파일 하나를 건드리기 전에, 모든 개념을 일상 비유로 먼저 설명합니다.

**핵심 기능:**

- **도구 비교 가이드** — Claude Code, Cursor, Windsurf, VS Code+Copilot, Google Antigravity 비교 추천
- **MCP 서버 설정** — 복사-붙여넣기 바로 가능한 JSON으로 MCP 서버 설치 및 연결
- **프로젝트 규칙 파일 생성** — `CLAUDE.md`, `.cursorrules`, `.windsurfrules`, `copilot-instructions.md`, `AGENTS.md` 자동 생성
- **Skills & SubAgent 생성** — `.claude/skills/`와 `.claude/agents/` 템플릿 자동 생성
- **Hook & Workflow 자동화** — `PreToolUse` / `PostToolUse` 훅과 멀티 에이전트 파이프라인 구성
- **도구 간 설정 마이그레이션** — 도구 간 설정 파일 즉시 변환
- **원클릭 프로젝트 셋업** — 프로젝트 유형별 전체 설정 스택 자동 생성
- **AI 비용 최적화** — 작업 유형별 최적 모델(Opus/Sonnet/Haiku) 추천
- **에러 자동 진단** — MCP/설정 파일 에러 자동 감지 및 수정

---

## 📦 설치 방법

`ai-coding-playground.md` 파일을 Claude Code 에이전트 폴더에 복사하세요:

```bash
# Mac / Linux
cp ai-coding-playground.md ~/.claude/agents/

# Windows
copy ai-coding-playground.md %USERPROFILE%\.claude\agents\
```

`CLAUDE.md` 설정 없이도 자동으로 활성화됩니다 (내장 자동 라우팅 키워드 포함).

---

## 🚀 사용 예시

설치 후 Claude Code에서 자연스럽게 말하면 활성화됩니다:

```
"MCP가 뭐야?"
"Cursor에서 MCP 설정해줘"
"코드 리뷰용 서브에이전트 만들어줘"
"Next.js 프로젝트 셋업해줘"
"커서 규칙을 Claude Code로 옮겨줘"
"어떤 AI 코딩 도구 써야 해?"
"MCP 서버가 안 켜져"
"AI 비용 줄이고 싶어"
```

---

## 🗺️ 학습 로드맵

에이전트가 6단계로 안내합니다:

| 레벨 | 주제 | 완성 목표 |
|------|------|----------|
| 1 | AI 코딩 도구 선택 & 설치 | 첫 AI 대화 |
| 2 | 프로젝트 규칙 파일 작성 | "항상 한국어로 답해줘" |
| 3 | Extension/Plugin 설치 | 유용한 Extension 3개 이상 |
| 4 | MCP 서버 연결 | MCP 서버 3개 이상 |
| 5 | Skills & SubAgent 생성 | 커스텀 Skill 1개 + SubAgent 1개 |
| 6 | Workflow & Orchestration | 코드 → 커밋 자동화 파이프라인 |

---

## 🛠️ 지원 도구 및 개념

| 분류 | 지원 목록 |
|------|----------|
| AI 코딩 도구 | Claude Code, Cursor, Windsurf, VS Code+Copilot, Google Antigravity |
| 규칙 파일 | CLAUDE.md, .cursorrules, .windsurfrules, copilot-instructions.md, AGENTS.md |
| MCP 서버 | filesystem, github, git, sqlite, postgres, fetch, context7, memory, sequential-thinking |
| Claude Code 전용 | Skills, SubAgent, Hooks, settings.json |
| 설명되는 개념 | MCP, Token, Context Window, API Key, 프롬프트 엔지니어링, 오케스트레이션 |

---

## 📋 핵심 설계 원칙

1. **절대 가정 금지** — 사용자가 터미널을 처음 보는 사람이라 가정하고 안내
2. **비유 우선** — 모든 개념은 일상 비유로 먼저 설명
3. **한국어 100%** — 모든 출력 한국어, 영어 용어에는 한국어 뜻 병기
4. **복사-붙여넣기 원칙** — 모든 설정 파일을 그대로 써도 바로 동작
5. **점진적 학습** — 한 번에 하나씩, 절대 단계를 건너뛰지 않음

---

## 📁 레포지토리 구조

```
ai-coding-playground/
└── ai-coding-playground.md   # Claude Code SubAgent 정의 파일
```

---

## 📄 라이선스

MIT License — Copyright (c) 2026 소담 AI 스튜디오

자세한 내용은 [LICENSE](./LICENSE)를 확인하세요.
