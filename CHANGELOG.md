# Changelog

Changes to the kit's structure and rules, newest first. Each entry says what
changed and the lesson from real use that prompted it.

## v0.2 — 2026-11-03

Lessons from the first week of running a real knowledge repository built on
this kit.

**Added**

- `today.md` — a running priority list across all projects. *Lesson:* "What
  should we do now?" was the most common opening question, and answering it
  meant reading every project. One short file answers it in one read.
- `templates/current.md` and `projects/PRJ-001/current.md` — a short "read
  first" state file per project. *Lesson:* `status.md` grows with every
  milestone, and reading it whole each session wastes the assistant's context
  and your usage limits. `status.md` stays as the history; `current.md` is the
  working memory.
- `templates/knowledge.md` — reusable lessons and how-tos, kept apart from
  status so they survive the project.
- `templates/reference.md` — one shared file for facts several projects rely
  on, with "the owning record wins" if they disagree. *Lesson:* the same few
  facts were being re-explained in every project.
- `templates/assistant-file.md` — a short tool-specific layer (`CLAUDE.md`,
  `GEMINI.md`) on top of `AGENTS.md`: session start and end rules and optional
  model routing.
- `prompts/end-of-session.md` — turns the end of a session into one reviewed
  update, with separate approval for content and for pushing.

**Changed**

- `AGENTS.md` — new "Start and end every session" section; reading order is now
  `today.md` → `current.md` → longer records only when needed; long files are
  searched, not read whole.
- `projects/index.md` — register hygiene: closed, merged and combined projects
  keep their IDs, plus a one-line load summary.
- Handoff files are named `YYYY-MM-DD-PRJ-NNN-topic.md`.
- `README.md` — updated layout, a "Why it works this way" section, and how to
  give feedback.

## v0.1 — 2026-10-29

First public release: two-repository model, evidence labels, approval and
classification policies, templates, a synthetic example project, a sample
handoff and a continuity-test prompt.
