# Content & On-Page SEO — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **content & on-page SEO** skills for **Claude, Claude Code, OpenAI Codex** and any agent that
reads the [Agent Skills](https://agentskills.io/specification) format. Each skill is a single `SKILL.md`: a senior
practitioner's workflow — when to use it, the inputs to ask for, a numbered process, decision rules, an output
template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/content-seo/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/content-seo-skills.git
cp -r content-seo-skills/keyword-research ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r content-seo-skills/keyword-research ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/content-seo/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`content-seo-audit`](content-seo-audit/SKILL.md) | Run a complete content and on-page SEO audit, scoring every page and deciding keep, improve, merge, redirect or remove. |
| [`keyword-research`](keyword-research/SKILL.md) | Find, size, group and prioritise the searches a business should target, mapped to pages. |
| [`search-intent-serp-analysis`](search-intent-serp-analysis/SKILL.md) | Work out what a searcher wants by reading the live results, and what a page must offer to compete. |
| [`topical-map`](topical-map/SKILL.md) | Plan pillars, clusters and supporting pages with one intent each, with hub-and-spoke internal links. |
| [`content-brief`](content-brief/SKILL.md) | Write a brief a writer (human or AI) can follow without guessing, with evidence and acceptance checks. |
| [`seo-content-writing`](seo-content-writing/SKILL.md) | Write and edit answer-first pages with evidence, no padding and no AI-sounding filler. |
| [`on-page-seo`](on-page-seo/SKILL.md) | Optimise a single page against its query and the ranking pages, as a scored checklist of exact edits. |
| [`title-tags-meta-descriptions`](title-tags-meta-descriptions/SKILL.md) | Write, audit and test titles and descriptions that match intent, earn clicks and survive rewrites. |
| [`image-seo`](image-seo/SKILL.md) | Make images findable, accessible and fast: file names, alt text, formats, sizes and sitemaps. |
| [`eeat-content-quality`](eeat-content-quality/SKILL.md) | Assess and improve content quality and E-E-A-T the way Google describes it, with YMYL care. |
| [`content-refresh`](content-refresh/SKILL.md) | Find decaying pages, diagnose why, and refresh them with real updates, measured against a baseline. |
| [`keyword-cannibalisation`](keyword-cannibalisation/SKILL.md) | Find pages competing for the same intent and fix them by merging, re-targeting or re-linking. |
| [`content-pruning`](content-pruning/SKILL.md) | Decide which low-value pages to remove, merge, redirect or noindex without losing traffic or links. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: content SEO skills, on-page SEO, SKILL.md, Agent Skills, Claude skills, Claude Code skills, Codex
skills, AI agent skills, keyword research, search intent, SERP analysis, topical map, content brief, content
writing, title tags, meta descriptions, image SEO, E-E-A-T, content refresh, cannibalisation, content pruning.</sub>
