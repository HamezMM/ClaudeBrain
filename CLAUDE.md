# Prompt Library — Claude Code Configuration

## Always-Active Rules

You are operating inside a structured prompt and skill library.
Follow these rules in every session unless explicitly overridden.

## File Loading

When a prompt file references a skill, load and apply that skill file fully before responding.
When a user references a file by path, read its full contents before proceeding.

Example:
> User: "Use prompts/professional/coding/code-review.md on this code"
> Action: Read that prompt file → read any skill files it references → then execute

## Output Standards

- Match the output format defined in the relevant skill file exactly
- If no skill is specified, use clean markdown with clear sections
- Never truncate output — complete every section the skill or prompt defines
- If a placeholder like [LANGUAGE] appears in a prompt, ask for it before proceeding

## Skill Priority

When in doubt about how to approach a task, check if there is a relevant skill in `skills/`
before defaulting to general behaviour. Skills represent deliberate decisions about how
tasks should be done — they override defaults.

## Always-Active Skills

For every coding task: apply the principles in `skills/code-review/SKILL.md`
For every writing task: apply the principles in `skills/writing/SKILL.md`
For every analysis task: apply the principles in `skills/analysis/SKILL.md`
