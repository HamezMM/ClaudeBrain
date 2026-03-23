---
title: Build Report
category: professional
subcategory: data
tags: [report, data, presentation]
skills: [skills/analysis/SKILL.md, skills/writing/SKILL.md]
works-with: [claude.ai, claude-code]
last-updated: 2026-03
---

## Purpose
Turn raw data or analysis findings into a clear, well-structured report for a specific audience.

## Load Skills
> Before proceeding, read and apply in order:
> 1. `skills/analysis/SKILL.md` — for findings and insight structure
> 2. `skills/writing/SKILL.md` — for clarity and narrative

## Prompt

```
Build a report from the following data or findings.

Report title / subject: [WHAT THIS REPORT IS ABOUT]
Audience: [WHO WILL READ THIS AND WHAT THEY CARE ABOUT]
Format needed: [EXECUTIVE SUMMARY / FULL REPORT / SLIDE OUTLINE / MEMO]
Key message: [THE ONE THING THIS REPORT MUST COMMUNICATE CLEARLY]
Data or findings to include: [PASTE DATA, BULLET POINTS, OR ANALYSIS]
Tone: [FORMAL / DIRECT / CONVERSATIONAL]
Length target: [SHORT / MEDIUM / AS LONG AS NEEDED]
```

## Usage Notes
- Defining the audience and key message first produces dramatically better output
- For slide outlines, Claude will suggest section titles and one-line summaries per slide
- If the data needs analysis first, run `analyze-dataset.md` before this prompt
