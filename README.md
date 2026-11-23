# ai-skill-plan-ship

Plan a change from a description, issue, or spec in its own git worktree, audit the plan, and wait for approval before implementing, testing, reviewing, and opening one pull request. Use when asked to "plan and ship" a feature or fix, or to take a change from idea to PR.

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-plan-ship
```

### Codex CLI

```bash
codex plugin marketplace add guillempuche/ai-skill-plan-ship
codex plugin add plan-ship@ai-skill-plan-ship
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-plan-ship

# Install plugin (plugin name is topic-only)
/plugin install plan-ship@guillempuche-ai-skill-plan-ship
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-plan-ship.git --path skills/plan-ship
```

### Antigravity

```bash
agy plugin install https://github.com/guillempuche/ai-skill-plan-ship
```

### Manual

Copy `skills/plan-ship` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
