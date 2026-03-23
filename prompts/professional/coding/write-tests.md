---
title: Write Tests
category: professional
subcategory: coding
tags: [tests, coverage, quality]
skills: [skills/code-review/SKILL.md]
works-with: [claude.ai, claude-code]
last-updated: 2026-03
---

## Purpose
Write tests for existing code, covering happy paths, edge cases, and failure modes.

## Load Skills
> Before proceeding, read and apply: `skills/code-review/SKILL.md`

## Prompt

```
Write tests for the following [LANGUAGE] code.

Testing framework: [e.g. Jest / Pytest / RSpec / Vitest]
Coverage goal: [happy path only / edge cases / full coverage]
Any known edge cases to cover: [LIST IF KNOWN]

[PASTE CODE HERE]
```

## Usage Notes
- Specify the testing framework — style and syntax differ significantly
- If the code has dependencies, mention them so mocks can be set up correctly
- "Full coverage" prompts more thorough output but takes longer to review
