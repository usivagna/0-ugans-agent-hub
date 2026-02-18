# Code Review Skill

A prompt/skill for performing high-signal code reviews.

## Usage

Use as a Copilot prompt file (`.github/copilot/code-review.prompt.md`) or as a manual prompt template.

---

## Prompt

Review the code changes with the following priorities:

1. **Bugs & Logic Errors** — Identify incorrect behavior, off-by-one errors, race conditions
2. **Security** — Flag injection risks, auth gaps, data exposure
3. **Performance** — Note unnecessary allocations, N+1 queries, missing indexes
4. **Maintainability** — Suggest improvements only when the benefit is clear

Do NOT comment on:
- Formatting or style (that's what linters are for)
- Trivial naming preferences
- Changes that are correct but differ from your preference
