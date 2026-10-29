# Knowledge Change Approval

**Purpose:** Turn proposals into accepted records without letting any AI
assistant expand its own authority.

## Roles

| Role | Does |
| --- | --- |
| **Owner** | Approves exact content, classification, audience, external sharing and consequential actions. |
| **Designated writer** | The single person or assistant that applies approved changes to the repository and verifies them. |
| **AI assistant** | Reads authorized sources, analyzes, and prepares proposals. Never approves its own proposals. |

Several assistants may work in parallel, but only one writer integrates changes.

## Lifecycle

1. **Prepare** — exact paths and content, the Git revision it's based on,
   purpose, evidence, classification, audience and risks.
2. **Authorize** — the owner accepts the content and separately authorizes each
   action needed (commit, push, share). One clear message can grant several
   approvals; none is assumed from another.
3. **Apply** — the writer rechecks the base revision and conflicts, then
   performs only the authorized operations.
4. **Verify** — check the resulting content, history and remote copy. Record
   the real outcome and any limitations.

Missing, ambiguous or withdrawn approval stops the operation.

## Actions that need their own authorization

- Creating a repository or changing its ownership or visibility.
- Commits, pushes and publication.
- Granting access or changing permissions.
- Changes in the data repository or connector settings.
- Transfers to new devices, services or AI providers.
- Deletion, backup, restore and encryption operations.
- Any automation or scheduled job.

## Conflicts

Start from a known revision. Never overwrite a record just because your copy is
newer. Keep competing versions until the owner reconciles them.

## Milestones

Every verified, notable milestone is captured in its project's `status.md`
(use `templates/milestone.md`). Qualifying events:

- Project creation, approval, pause or closure.
- Major decisions or requirement changes.
- Completed phases or accepted deliverables.
- Significant findings or resolved defects.
- Material architecture or configuration changes.
- New dependencies, blockers or critical risks.
- Changed ownership, authority or approval status.
- Lessons that materially affect future work.

Skip routine conversation, brainstorming, trivial progress and duplicates.

Each milestone records: ID and date, previous and resulting state, what changed,
its source and evidence label, approval status, and the remaining action.
Consequential or disputed events also record verification method, confidence,
exact approval reference, risks, and created/updated timestamps.

Use `UNKNOWN` (with a reason) rather than guessing. An approved draft or a
commit does not prove the underlying work happened.

## Retention and withdrawal

Decide separately how long drafts, accepted records and backups are kept. If
approval is withdrawn, check where the content already went; withdrawal is not
the same as verified deletion.
