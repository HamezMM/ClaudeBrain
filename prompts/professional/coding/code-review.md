---
title: Code Review
category: professional
subcategory: coding
tags: [review, quality, code]
skills: [skills/code-review/SKILL.md]
works-with: [claude.ai, claude-code]
last-updated: 2026-03
---

## Purpose
Review code for quality, correctness, security, and improvements.

## Load Skills
> Before proceeding, read and apply: `skills/code-review/SKILL.md`

## Prompt

```
Review the following [LANGUAGE] code.

Context: [WHAT THIS CODE DOES / WHERE IT FITS IN THE PROJECT]
Focus areas: [quality / security / performance / readability / all]
Anything specific to check: [ANY KNOWN CONCERNS OR AREAS OF DOUBT]

[PASTE CODE HERE]
```

## Usage Notes
- Specifying focus areas narrows the review — useful if you're short on time
- For large files, consider pasting one function or section at a time
- In Claude Code, use `@` to reference the file directly instead of pasting
