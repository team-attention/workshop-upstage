# 산으로 가는 AI 조련법

> Upstage Workshop — CC를 제대로 부리는 기술

2026.02.25 | Upstage 엔지니어 대상 Claude Code 워크숍

## 설치

```bash
npx skills add team-attention/workshop-upstage --agent claude-code --yes
```

이 한 줄이면 워크숍에서 사용하는 모든 스킬이 Claude Code에 설치됩니다. 특정 스킬만 설치하려면:

```bash
# Clarify 렌즈 — 모호한 요구사항 명확화
npx skills add team-attention/workshop-upstage --skill vague --agent claude-code --yes

# Clarify 렌즈 — Unknown Unknown 탐지
npx skills add team-attention/workshop-upstage --skill unknown --agent claude-code --yes

# Clarify 렌즈 — Content vs Form (Metamedium)
npx skills add team-attention/workshop-upstage --skill metamedium --agent claude-code --yes

# 팀 어셈블 — 멀티 에이전트 전문가 팀 구성
npx skills add team-attention/workshop-upstage --skill team-assemble --agent claude-code --yes

# Wrap — 세션 마무리 + 인사이트 추출
npx skills add team-attention/workshop-upstage --skill wrap --agent claude-code --yes

# Compound — 인사이트를 복리로 축적
npx skills add team-attention/workshop-upstage --skill compound --agent claude-code --yes
```

## 오늘의 구조

| 시간 | 파트 | 핵심 |
|------|------|------|
| 1시간 | 조련법 | Clarify 렌즈 + 멀티 프로토타이핑 + Wrap/Compound |
| 2시간 | 해커톤 | 직접 문제 해결 — more token, more wins |
| 1시간 | 발표 | 결과물 시연 + 피드백 |

"배웠습니다"가 아니라 **"만들었습니다"**

CLAUDE.md + Skill = 지식이 복리로 쌓이는 구조

## Skills

```
.claude/skills/
├── vague/          # 모호한 요구사항을 구조화된 질문으로 명확화
├── unknown/        # Unknown Unknown을 사전에 탐지하여 리스크 제거
├── metamedium/     # Content vs Form — Alan Kay의 메타미디엄 렌즈
├── team-assemble/  # 전문가 에이전트 팀을 자동 구성
├── wrap/           # 세션 마무리 + 5개 전문 에이전트로 인사이트 추출
└── compound/       # 인사이트를 구조화된 문서로 축적 (복리 성장)
```

## License

MIT
