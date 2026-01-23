## Quick context

This repository is a collection of Markdown writing (prose, poetry, drafts, and research notes). There is no build system, runtime, or automated tests — content is edited as plain `.md` files and organized by topical folders.

Top-level folders you will interact with (examples):
- `content/` — long-form drafts (e.g. `content/first_draft.md`).
- `poetry/` — poems and haiku collections (e.g. `poetry/haiku_repo.md`).
- `research/` — notes and research (e.g. `research/eloni_data.md`).
- `prose_porn/` — writing collections (e.g. `prose_porn/collection.md`).
- `love's_farewell/`, `avalon/`, `rough_writes/`, `ideas/` — other thematic folders for drafts and fragments.

## Purpose for AI edits

When editing or proposing new content, be conservative: preserve author's voice and structure, prefer small focused edits, and avoid renaming or moving existing files without explicit confirmation.

Do these things first:
- Look for a target file (example: `content/first_draft.md`) and make minimal, traceable edits.
- If creating new material, add a single `.md` file in the appropriate folder and use a short, descriptive filename (lowercase, underscores are common).

Project-specific patterns and conventions (discoverable from the repo):
- All content is Markdown (`.md`). No frontmatter was found in top-level files; do not inject YAML frontmatter unless requested.
- Filenames are generally lowercase with underscores and short phrases (e.g. `first_day_of_summer.md`, `what_you_mean_to_me.md`). Match this style for new files.
- Directories group by theme rather than by format: pick the folder that matches subject matter (e.g. research notes go to `research/`).

Editing rules and examples
- Small edits only: prefer line-level or paragraph-level changes (typos, clarity, flow) rather than wholesale rewrites.
- Preserve section ordering unless the change improves narrative flow and you explain why in the commit/PR description.
- Example: to tighten a sentence in the first draft, edit `content/first_draft.md` and keep surrounding paragraphs unchanged.
- Example: to add a haiku, create `poetry/my_short_haiku.md` containing the three-line poem.

What to avoid
- Do not rename or move files without explicit approval from the repo owner.
- Don't add build-related files, dependencies, or CI config — this repo contains only content.
- Avoid inserting metadata blocks or changing file encodings.

Commit & PR guidance (workflow-facing)
- This repository is content-first. For any non-trivial change, create a small branch and open a PR with:
  - The list of files changed (paths).
  - A short rationale focused on content and voice.
  - Notes on any structural changes (moves/renames) — these should be rare and explicitly approved.

Useful files to inspect before editing
- `content/first_draft.md` — example long-form draft.
- `poetry/haiku_repo.md` — poem collection style.
- `research/eloni_data.md` — note/research style and tone.

If uncertain
- When a requested change would touch multiple files, rename a file, or alter the repository structure, summarize the proposed change in a comment or draft PR and ask the maintainer before applying.

Feedback request
- If anything above is unclear or you'd like more detailed examples (commit message templates, branch naming, or acceptable rewrite scope), ask and I'll expand this file.

---
_Generated automatically by an assistant to help agent contributors get started in this writing-focused repo._
