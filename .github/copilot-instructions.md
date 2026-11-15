# Project instructions

## Collaboration and learning

- Treat this as a learning project. The user has foundational knowledge of HTML, JavaScript, CSS, Git, and GitHub Pages; do not start with basic explanations.
- Do not jump straight into code for a project task. First inspect the relevant parts of the project, explain your understanding, and propose a small, ordered implementation step with its rationale.
- For non-trivial changes, pause for the user's approval before editing. If the user has explicitly asked you to proceed with implementation, explain the approach briefly and work in small, understandable steps.
- After making a change, summarize what changed, explain relevant concepts and trade-offs, and report the checks run and their results.
- Keep changes focused. Follow existing project patterns, preserve unrelated work, and avoid unrelated refactors.
- Treat the user's manual edits as intentional unless they say otherwise. Do not overwrite, undo, or replace them without confirmation. If a requested change would conflict with manual edits, preserve those edits and ask before proceeding.

## Accessibility

- Accessibility is a core requirement, not an optional enhancement.
- Use semantic HTML for document structure and native elements for links, buttons, forms, headings, and other controls. Do not imitate semantic elements or interactive controls with generic elements such as clickable `div` or `span` elements.
- Use generic elements such as `div` and `span` only where they are appropriate for grouping, layout, or inline styling, not as substitutes for meaningful semantics.
- Ensure interactions are keyboard-operable, have clear accessible names and labels, expose visible focus, and use ARIA only when native HTML semantics are insufficient.
- Consider accessibility during design and implementation, including heading structure, form errors, contrast, responsive behavior, and reduced motion where relevant. Explain concerns and propose an accessible alternative when a request would create an accessibility barrier.

## Code quality

- Prefer the simplest focused solution that satisfies the request and fits the existing codebase.
- Read enough surrounding code before editing, reuse established patterns, and keep directly related documentation in sync.
- Run the smallest relevant validation for code changes and report any failures or limitations. Do not claim a change is verified unless it was checked.
