---
title: Design System Audit
category: professional
subcategory: design
tags: [design-system, audit, consistency]
skills: [skills/design/SKILL.md, skills/analysis/SKILL.md]
works-with: [claude.ai, claude-code]
last-updated: 2026-03
---

## Purpose
Audit an existing design system or component library for gaps, inconsistencies, and improvements.

## Load Skills
> Before proceeding, read and apply in order:
> 1. `skills/design/SKILL.md` — for design assessment
> 2. `skills/analysis/SKILL.md` — for structured audit output

## Prompt

```
Audit the following design system.

What exists today: [DESCRIBE OR PASTE THE CURRENT SYSTEM — TOKENS, COMPONENTS, PATTERNS]
Platform: [WEB / IOS / ANDROID / CROSS-PLATFORM]
Team size using it: [HOW MANY DESIGNERS / DEVELOPERS RELY ON THIS]
Main pain points: [WHAT'S CAUSING PROBLEMS TODAY]
Goal of this audit: [CONSISTENCY / SCALABILITY / HANDOFF / FULL REVIEW]
```

## Usage Notes
- Paste component names, token lists, or usage descriptions for a more specific audit
- Works well when combined with a Figma or Storybook description pasted inline
- For large systems, audit one layer at a time: foundations → components → patterns
