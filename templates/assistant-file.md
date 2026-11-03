# <Assistant> Working Instructions

> Template for a tool-specific instruction file. Save it at the repository root
> under the name your assistant looks for (for example `CLAUDE.md` or
> `GEMINI.md`). It **adds** to `AGENTS.md`; it never replaces or overrides it.
> Keep it short: every assistant reads it at the start of every session.

**Classification:** Internal
**Status:** OWNER DECISION — accepted YYYY-MM-DD.

Follow [AGENTS.md](AGENTS.md) in full. This file adds only rules specific to
<assistant>.

## Start of every session

1. Name the project ID and the task.
2. Read [today.md](today.md), then the project's `current.md` (or `overview.md`
   if it has none).
3. Open `status.md`, `knowledge.md` or other long records only when the task
   needs them, and search within them rather than reading them whole.

## Choosing a model (optional)

Match effort to the step so routine work doesn't burn your plan's limits.

| Step type | Model tier | Effort |
| --- | --- | --- |
| Architecture, decisions, audits | Strongest | High |
| Planning a phase, reviewing work | Strongest | Medium |
| Building, configuring, coding | Mid | Medium |
| Drafting, summarizing | Mid | Low–medium |
| Bulk extraction, classification | Fastest | Low |

Escalate only after the cheaper tier fails twice on the same problem.

## End of every session

Draft the update to the project's `current.md` and to `today.md` for the owner
to accept (see [prompts/end-of-session.md](prompts/end-of-session.md)).
Nothing is committed without the owner's explicit approval.
