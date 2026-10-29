# Milestone entry template

Copy one of these into the project's `status.md` under **Milestones**.

## Core entry (most milestones)

```markdown
### M-NNNN — <Title> (YYYY-MM-DD)

- **Type:** decision | phase complete | finding | blocker | closure | lesson
- **Change:** <previous state> → <resulting state>. <What changed, in a sentence.>
- **Evidence:** <VERIFIED | OWNER DECISION | DOCUMENT CLAIM | …> — <source, and how/when checked>
- **Completion basis:** independently verified | owner-reported | source-reported | not applicable
- **Approval:** ACCEPTED (<reference>) | PENDING | NOT APPLICABLE
- **Next:** <remaining action or blocker>
```

## Extended entry (consequential, disputed or high-impact)

Add these fields to the core entry:

```markdown
- **Source version:** <commit SHA, document version or file hash>
- **Verification:** <method> on <YYYY-MM-DD>
- **Confidence:** HIGH | MEDIUM | LOW — <reason>
- **Approval scope:** <exactly what was approved, and what was not>
- **Risks and dependencies:** <list>
- **Recorded:** <ISO 8601 with offset> · **Updated:** <ISO 8601 with offset>
```

Use `UNKNOWN — <reason>` instead of guessing any field.
