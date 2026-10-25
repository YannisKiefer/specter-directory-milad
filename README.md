<div align="center">

# 📚 Awesome Agent Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated list of Agent Skills (`SKILL.md`) for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![Stars](https://img.shields.io/github/stars/milad-ahmd/awesome-agent-skills?style=social)](https://github.com/milad-ahmd/awesome-agent-skills)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

</div>

> **What's a skill?** A folder with a `SKILL.md` file (YAML frontmatter `name` + `description`, followed by instructions), plus optional scripts and resources. The agent loads it automatically when the task matches the description.

## Contents

- [Getting started](#getting-started)
- [Collections](#collections)
- [Git & workflow](#git--workflow)
- [Code review & quality](#code-review--quality)
- [Security & maintenance](#security--maintenance)
- [DevOps & backend](#devops--backend)
- [Documentation](#documentation)
- [Growth](#growth)
- [Marketing & social media](#marketing--social-media)
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

## Collections

- [milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills) - 31 practical skills for developers and marketers with a one-line installer.

## Git & workflow

- [commit-craft](https://github.com/milad-ahmd/commit-craft) - Split messy changes into atomic Conventional Commits.
- [meeting-notes-to-tickets](https://github.com/milad-ahmd/meeting-notes-to-tickets) - Meeting notes into de-duplicated GitHub, Linear or Jira tickets.
- [migration-wizard](https://github.com/milad-ahmd/migration-wizard) - Phased, verified codebase migrations (JS→TS, Jest→Vitest, Pages→App Router).
- [changelog-from-git](https://github.com/milad-ahmd/changelog-from-git) - Human-readable release notes from git history.

## Code review & quality

- [pr-reviewer-pro](https://github.com/milad-ahmd/pr-reviewer-pro) - Senior-engineer PR reviews with severity levels, `file:line` evidence and suggested fixes.
- [test-gap-hunter](https://github.com/milad-ahmd/test-gap-hunter) - Find the riskiest untested code and write tests in the project's framework.
- [screenshot-to-component](https://github.com/milad-ahmd/screenshot-to-component) - Screenshot to a component built with the project design system.
- [a11y-fixer](https://github.com/milad-ahmd/a11y-fixer) - WCAG 2.2 AA audit that fixes issues in code.

## Security & maintenance

- [env-secrets-guard](https://github.com/milad-ahmd/env-secrets-guard) - Detect leaked secrets and guide safe rotation.
- [dependency-doctor](https://github.com/milad-ahmd/dependency-doctor) - Vulnerability and outdated-package audit with a safe upgrade plan.

## DevOps & backend

- [dockerize-anything](https://github.com/milad-ahmd/dockerize-anything) - Production-ready multi-stage Dockerfile and compose.
- [api-to-sdk](https://github.com/milad-ahmd/api-to-sdk) - Typed client SDK from an OpenAPI spec or backend routes.
- [sql-optimizer](https://github.com/milad-ahmd/sql-optimizer) - Explain slow queries, read EXPLAIN plans, suggest indexes.

## Documentation

- [readme-glow-up](https://github.com/milad-ahmd/readme-glow-up) - Rewrites READMEs into star-worthy pages using only facts found in the repo.
- [codebase-explainer](https://github.com/milad-ahmd/codebase-explainer) - Onboarding guide with Mermaid architecture diagrams.

## Growth

- [launch-post-writer](https://github.com/milad-ahmd/launch-post-writer) - X thread, Show HN, LinkedIn and Reddit launch posts from a repo.
- [landing-page-roaster](https://github.com/milad-ahmd/landing-page-roaster) - Scored, honest roast of a landing page plus copy rewrites.

## Marketing & social media

- [instagram-growth-manager](https://github.com/milad-ahmd/instagram-growth-manager) - Grow and manage Instagram with bio audits, Reels scripts, carousels, captions, hashtags and growth reviews.
- [tiktok-viral-creator](https://github.com/milad-ahmd/tiktok-viral-creator) - TikTok ideas, 2-second hooks, shot-by-shot scripts and retention analysis.
- [youtube-seo-optimizer](https://github.com/milad-ahmd/youtube-seo-optimizer) - YouTube titles, thumbnails, descriptions, chapters and channel audits for more views.
- [youtube-script-writer](https://github.com/milad-ahmd/youtube-script-writer) - High-retention YouTube and Shorts scripts with hooks, open loops and B-roll cues.
- [content-repurposer](https://github.com/milad-ahmd/content-repurposer) - One video or podcast into 15+ posts: Shorts, Reels, threads, LinkedIn, carousel, newsletter.
- [social-media-calendar](https://github.com/milad-ahmd/social-media-calendar) - Monthly cross-platform content calendar, exported as CSV for Notion, Sheets, Buffer or Later.
- [hook-generator](https://github.com/milad-ahmd/hook-generator) - Scroll-stopping hooks for videos, posts, emails and ads, scored and ranked.
- [ad-copy-generator](https://github.com/milad-ahmd/ad-copy-generator) - Ad copy for Meta, TikTok, Google and YouTube within each platform's limits, plus an A/B test matrix.
- [seo-blog-writer](https://github.com/milad-ahmd/seo-blog-writer) - SEO blog posts that rank: intent research, outline, meta tags, FAQ and schema.
- [email-campaign-writer](https://github.com/milad-ahmd/email-campaign-writer) - Welcome, launch, cart and newsletter email sequences with subject-line tests.
- [brand-voice-guide](https://github.com/milad-ahmd/brand-voice-guide) - A brand voice, positioning and personas guide, then rewrites copy on-brand.
- [competitor-spy](https://github.com/milad-ahmd/competitor-spy) - Competitor analysis of pricing, messaging, socials, ads and reviews, with a SWOT and opportunities.
- [influencer-outreach](https://github.com/milad-ahmd/influencer-outreach) - Influencer and UGC campaigns: vetting, outreach DMs, briefs and tracking.
- [social-analytics-reporter](https://github.com/milad-ahmd/social-analytics-reporter) - Social media analytics exports into a clear report with KPIs, reasons and next actions.

## Ideas wanted

Skills nobody has built well yet. Build one and open a PR to add it:

- `migration-wizard` - JS→TS, Jest→Vitest, Pages→App Router
- `sql-explainer-optimizer` - explain slow queries and suggest indexes

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first.

<div align="center">

**If you find this list useful, a ⭐ helps others find it.**

</div>
