# Contributing to the Prompt Library

## Adding a New Prompt

1. Copy `templates/new-prompt-template.md` into the correct category folder
2. Name the file clearly using lowercase and hyphens: `my-prompt-name.md`
3. Fill in all frontmatter fields
4. If the prompt depends on a skill, add a `## Load Skills` section
5. Add a row to the README index table
6. Commit and Sync Now in Claude.ai

## Adding a New Skill

Only create a new skill if:
- More than one prompt will use it, OR
- An existing prompt has process/output requirements complex enough to warrant it

1. Copy `templates/new-skill-template.md` into `skills/[skill-name]/SKILL.md`
2. Fill in all sections — especially Pitfalls and Quality Bar
3. Update the `used-by` frontmatter field
4. Update the Skill Index in README
5. Commit and Sync Now in Claude.ai

## Updating an Existing Skill

When a skill produces a bad result, add the lesson to its Pitfalls section.
When a skill produces an exceptionally good result, note what made it work in Quality Bar.
Date the update in the frontmatter.

## Rules

- Every prompt must use the template
- Never leave [PLACEHOLDER] text unfilled in a skill file
- The README index must always reflect the current state of the repo
- Skills are shared — changes affect every prompt that references them
