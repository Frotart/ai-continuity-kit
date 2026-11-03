# Changelog

Changes to the kit's structure and rules, newest first. Each entry says what
changed and the lesson from real use that prompted it.

## v0.3 — 2026-11-03

Ideas borrowed from popular agent-tooling projects, kept within the kit's
"you approve everything" model.

**Added**

- `AGENTS.md` section 3, "Write entries others can find": entry types
  (decision, lesson, gotcha, open question) beside the evidence label;
  `DEC-NNN-NN` decision IDs; searchable first lines; **(not repeat-safe)**
  marks on procedure steps. *Lesson:* decisions retold in several places
  drifted apart, and re-running a destructive step after an error is an easy
  mistake.
- Off-record rule and "screens and captures stay out" in `AGENTS.md`
  section 4. *Lesson:* curious side questions were being drafted into project
  records, and screenshots from browser automation carry private details.
- Parallel-session branches and revision re-checks in `AGENTS.md` section 5.
  *Lesson:* two sessions drafting against different revisions overwrite each
  other.
- `docs/why-evidence-labels.md` — the idea behind the labels, in plain words.
- `docs/assets/how-it-works.svg` — diagram replacing the ASCII sketch.
- `CONTRIBUTING.md` and issue templates for friction reports and adaptations.
- README: two-minute start, "Who it's for", "How it compares", "I want to…"
  table and FAQ.

**Changed**

- Reading order now ends with the data repository, opened only when a summary
  isn't evidence enough.
- `templates/status.md` and the synthetic PRJ-001 records use decision IDs;
  `templates/knowledge.md` gains a Gotchas section; `templates/milestone.md`
  adds the gotcha type.
- `prompts/end-of-session.md` asks for decision IDs, lessons and gotchas, and
  skips off-record parts of the chat.
- `AGENTS.md` sections renumbered: former 3–8 are now 4–9.

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
