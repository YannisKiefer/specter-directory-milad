<div align="center">

# 📚 Awesome Agent Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated list of Agent Skills (`SKILL.md`) for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![Stars](https://img.shields.io/github/stars/milad-ahmd/awesome-agent-skills?style=social)](https://github.com/milad-ahmd/awesome-agent-skills)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

</div>

> **What's a skill?** A folder with a `SKILL.md` file (YAML frontmatter `name` + `description`, followed by instructions), plus optional scripts and resources. The agent loads it automatically when the task matches the description.

## Contents

- [Getting started](#getting-started)
- [Code review & quality](#code-review--quality)
- [Documentation](#documentation)
- [Ideas wanted](#ideas-wanted)
- [Contributing](#contributing)

## Getting started

Install any skill by copying its folder into `~/.claude/skills/` (global) or `<project>/.claude/skills/` (per project). Tools that don't support skills natively can use the `SKILL.md` content as a rules or system-prompt file.

Minimal skill template:

```markdown
---
name: my-skill
description: What it does and WHEN the agent should use it.
---

# My Skill
Step-by-step instructions, rules, and output format.
```

## Code review & quality

- [pr-reviewer-pro](https://github.com/milad-ahmd/pr-reviewer-pro) - Senior-engineer PR reviews with severity levels, `file:line` evidence and suggested fixes.

## Documentation

- [readme-glow-up](https://github.com/milad-ahmd/readme-glow-up) - Rewrites READMEs into star-worthy pages using only facts found in the repo.

## Ideas wanted

Skills nobody has built well yet. Build one and open a PR to add it:

- `commit-craft` - split messy changes into atomic Conventional Commits
- `test-gap-hunter` - find untested code and write tests in the project's framework
- `dependency-doctor` - safe upgrade plans with breaking-change notes
- `migration-wizard` - JS→TS, Jest→Vitest, Pages→App Router
- `a11y-fixer` - WCAG audit plus fixes
- `dockerize-anything` - production-ready Dockerfile and compose
- `changelog-from-git` - release notes from a commit range
- `sql-explainer-optimizer` - explain slow queries and suggest indexes

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first.

<div align="center">

**If you find this list useful, a ⭐ helps others find it.**

</div>
