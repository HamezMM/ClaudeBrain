# Prompt Library

A structured library of prompts and skills for use with Claude.ai Projects and Claude Code.

## How to Use

**Claude.ai (this Project):**
Reference any file by its path in conversation.
> *"Use `prompts/professional/design/design-brief.md` to write a brief for this project"*

**Claude Code:**
Use `@` mentions to load files directly into context.
> `@prompts/professional/coding/code-review.md`

**Always-active rules** are set in `CLAUDE.md` (Claude Code) and the Project system prompt (Claude.ai).

> ⚠️ After updating any file in the repo, click **Sync Now** in the GitHub integration panel to refresh Claude's project knowledge.

---

## Repo Structure

```
prompt-library/
├── README.md                               ← master index (this file)
├── CLAUDE.md                               ← always-active rules for Claude Code
├── PROJECT_SYSTEM_PROMPT.md                ← paste into Claude.ai Project settings
│
├── templates/
│   ├── new-prompt-template.md
│   └── new-skill-template.md
│
├── prompts/
│   ├── professional/
│   │   ├── design/
│   │   │   ├── design-brief.md
│   │   │   ├── design-critique.md
│   │   │   └── design-system-audit.md
│   │   ├── writing/
│   │   │   ├── edit-for-clarity.md
│   │   │   └── draft-email.md
│   │   ├── coding/
│   │   │   ├── code-review.md
│   │   │   └── write-tests.md
│   │   ├── business/
│   │   │   ├── strategic-analysis.md
│   │   │   └── meeting-prep.md
│   │   └── data/
│   │       ├── analyze-dataset.md
│   │       └── build-report.md
│   └── personal/
│       ├── health/
│       │   ├── workout-plan.md
│       │   └── meal-plan.md
│       ├── finance/
│       │   ├── budget-review.md
│       │   └── financial-goal-plan.md
│       ├── learning/
│       │   ├── research-topic.md
│       │   └── learn-a-skill.md
│       ├── home/
│       │   ├── home-project-plan.md
│       │   └── household-systems.md
│       └── creative/
│           ├── brainstorm.md
│           └── develop-creative-project.md
│
└── skills/
    ├── design/SKILL.md
    ├── writing/SKILL.md
    ├── code-review/SKILL.md
    ├── analysis/SKILL.md
    ├── planning/SKILL.md
    ├── research/SKILL.md
    └── home-admin/SKILL.md
```

---

## Prompt Index

### Professional — Design

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Design Brief](prompts/professional/design/design-brief.md) | [design](skills/design/SKILL.md) | Starting any creative project |
| [Design Critique](prompts/professional/design/design-critique.md) | [design](skills/design/SKILL.md) | Getting structured feedback on work |
| [Design System Audit](prompts/professional/design/design-system-audit.md) | [design](skills/design/SKILL.md) + [analysis](skills/analysis/SKILL.md) | Reviewing a component library for gaps |

### Professional — Writing

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Edit for Clarity](prompts/professional/writing/edit-for-clarity.md) | [writing](skills/writing/SKILL.md) | Tightening any piece of writing |
| [Draft Email](prompts/professional/writing/draft-email.md) | [writing](skills/writing/SKILL.md) | Writing professional emails from scratch |

### Professional — Coding

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Code Review](prompts/professional/coding/code-review.md) | [code-review](skills/code-review/SKILL.md) | Reviewing code for quality |
| [Write Tests](prompts/professional/coding/write-tests.md) | [code-review](skills/code-review/SKILL.md) | Adding test coverage |

### Professional — Business

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Strategic Analysis](prompts/professional/business/strategic-analysis.md) | [analysis](skills/analysis/SKILL.md) + [planning](skills/planning/SKILL.md) | Evaluating any decision or opportunity |
| [Meeting Prep](prompts/professional/business/meeting-prep.md) | [planning](skills/planning/SKILL.md) | Preparing for an important meeting |

### Professional — Data

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Analyze Dataset](prompts/professional/data/analyze-dataset.md) | [analysis](skills/analysis/SKILL.md) | Making sense of data or results |
| [Build Report](prompts/professional/data/build-report.md) | [analysis](skills/analysis/SKILL.md) + [writing](skills/writing/SKILL.md) | Turning data into a presentable report |

---

### Personal — Health & Fitness

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Workout Plan](prompts/personal/health/workout-plan.md) | [planning](skills/planning/SKILL.md) | Building a training schedule |
| [Meal Plan](prompts/personal/health/meal-plan.md) | [planning](skills/planning/SKILL.md) | Planning weekly meals around goals |

### Personal — Finance & Budgeting

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Budget Review](prompts/personal/finance/budget-review.md) | [analysis](skills/analysis/SKILL.md) | Reviewing spending and finding improvements |
| [Financial Goal Plan](prompts/personal/finance/financial-goal-plan.md) | [analysis](skills/analysis/SKILL.md) + [planning](skills/planning/SKILL.md) | Turning a financial goal into a concrete plan |

### Personal — Learning & Research

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Research Topic](prompts/personal/learning/research-topic.md) | [research](skills/research/SKILL.md) | Learning something new thoroughly |
| [Learn a Skill](prompts/personal/learning/learn-a-skill.md) | [research](skills/research/SKILL.md) + [planning](skills/planning/SKILL.md) | Building a structured learning path |

### Personal — Home & Life Admin

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Home Project Plan](prompts/personal/home/home-project-plan.md) | [home-admin](skills/home-admin/SKILL.md) + [planning](skills/planning/SKILL.md) | Planning any renovation or home project |
| [Household Systems](prompts/personal/home/household-systems.md) | [home-admin](skills/home-admin/SKILL.md) | Creating routines and systems that stick |

### Personal — Creative Projects

| Prompt | Skills Used | Use When |
|--------|-------------|----------|
| [Brainstorm](prompts/personal/creative/brainstorm.md) | none | Generating ideas — quantity over polish |
| [Develop Creative Project](prompts/personal/creative/develop-creative-project.md) | [design](skills/design/SKILL.md) + [planning](skills/planning/SKILL.md) | Taking an idea from vague to defined |

---

## Skill Index

| Skill | Used By | What It Governs |
|-------|---------|-----------------|
| [design](skills/design/SKILL.md) | design-brief, design-critique, design-system-audit, develop-creative-project | Briefs, critiques, system audits, creative direction |
| [writing](skills/writing/SKILL.md) | edit-for-clarity, draft-email, build-report | Editing standards, draft quality, output format |
| [code-review](skills/code-review/SKILL.md) | code-review, write-tests | Review process, severity levels, output format |
| [analysis](skills/analysis/SKILL.md) | strategic-analysis, analyze-dataset, build-report, budget-review, financial-goal-plan | Structured assessment, insight format, recommendations |
| [planning](skills/planning/SKILL.md) | strategic-analysis, meeting-prep, workout-plan, meal-plan, financial-goal-plan, learn-a-skill, home-project-plan, develop-creative-project | Goal-first planning, constraint handling, checkpoint format |
| [research](skills/research/SKILL.md) | research-topic, learn-a-skill | Depth of coverage, contested areas, next-step guidance |
| [home-admin](skills/home-admin/SKILL.md) | home-project-plan, household-systems | Project sequencing, vendor briefs, household system design |

---

## Adding New Prompts or Skills

1. Copy `templates/new-prompt-template.md` or `templates/new-skill-template.md`
2. Fill in all frontmatter fields — especially `skills:` references
3. Add a `## Load Skills` section if the prompt depends on a skill
4. Add a row to the relevant table in this README
5. Commit and **Sync Now** in Claude.ai
