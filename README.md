[![skills.sh](https://skills.sh/b/ruwaifatahir/skills)](https://skills.sh/ruwaifatahir/skills)

# Skills

Agent Skills I use and share. Each skill is a folder under [`skills/`](./skills)
with a `SKILL.md` that follows the open [Agent Skills spec](https://agentskills.io/specification),
so it works in Claude Code, Claude.ai, Codex, Cursor, and other agents that read skills.

## Skills

| Skill | What it does |
| --- | --- |
| [recall-drill](./skills/recall-drill) | Quizzes you on something you just read. You write down everything you remember, closed-book; it grades that against the source and cues each gap before revealing it. Built on retrieval-practice research ([evidence](./skills/recall-drill/references/EVIDENCE.md)). |

## Install

### Any agent (skills CLI)

```bash
npx skills add ruwaifatahir/skills
```

One skill only:

```bash
npx skills add ruwaifatahir/skills --skill recall-drill
```

### Claude Code plugin marketplace

```
/plugin marketplace add ruwaifatahir/skills
/plugin install recall-drill@ruwaifatahir-skills
```

### Manual

Copy the skill folder into your agent's skills directory, for example
`~/.claude/skills/recall-drill/` for Claude Code.

## Usage

Read something, then ask your agent:

- "quiz me on this"
- "test me on what I just read"
- "drill me on chapter 3" (with a file path or URL)

## License

[MIT](./LICENSE)
