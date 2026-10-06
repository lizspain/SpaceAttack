# Project guidance

## Product and implementation goals

- Build a simple Space Invaders style game as a browser app using Canvas and plain JavaScript.
- Keep the app in `index.html` unless the project needs a clear, practical reason to split files.
- Favor readable, maintainable code and a clear component structure over unnecessary abstraction.
- Prefer the simplest implementation that supports the requested game behavior.
- Preserve the existing UI unless the user explicitly requests a visual change.
- Before making a large architectural change, explain its tradeoffs and get direction.
- Limit changes to the requested scope; do not modify unrelated parts of the project.

## Workflow

- After each project prompt, record the full prompt in `outputs/space-attack-prompts/prompts.xlsx`, in chronological order, with a Pacific Time timestamp and the prompt text in separate columns.
- Do not run separate tests or validation for prompt-log workbook updates unless the user asks; keep workbook logging lightweight.
- After each prompt, include a link to `index.html` in the response so the designer can open or refresh it manually.
- After implementation, run the relevant build or verification command. If there is no configured build or test system, use a focused check appropriate to the change and state what was checked.
- Keep this document aligned with the user's latest project preferences.
