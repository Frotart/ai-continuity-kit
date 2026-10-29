# PRJ-001 — Status

> **SYNTHETIC EXAMPLE.** Shows how labels, milestones and the next safe action
> fit together.

**Classification:** Internal
**Last reviewed:** 2026-03-20

## Current checkpoint

**State:** Active — mesh installed; desk cabling waiting on a quote.

**Next safe action:** Ask the owner whether to accept the cabling quote once it
arrives. Nothing else needs doing until then.

## Decisions

| Date | Label | Decision |
| --- | --- | --- |
| 2026-03-02 | OWNER DECISION | Two-unit mesh system; hardware budget 200. |
| 2026-03-14 | OWNER DECISION | Keep the old router as a fallback until 2026-04-15, then return it. |

## Open gates and risks

- [ ] Cabling quote received and accepted.
- [ ] One week of use with no drop-outs (starts after cabling).
- [ ] Old router returned by 2026-04-15.

## What remains unverified

- Upstairs speed figures were owner-reported from a phone test; not repeated.
- Guest-network isolation is configured but has not been tested from a guest
  device.

## Milestones

### M-0003 — Mesh installed and working (2026-03-14)

- **Type:** phase complete
- **Change:** old router only → mesh system live on both floors.
- **Evidence:** DOCUMENT CLAIM — owner's install notes; upstairs speed
  owner-reported.
- **Completion basis:** owner-reported
- **Approval:** NOT APPLICABLE
- **Next:** test guest isolation; obtain cabling quote.

### M-0002 — Hardware chosen (2026-03-02)

- **Type:** decision
- **Change:** options open → two-unit mesh selected.
- **Evidence:** OWNER DECISION — chat with owner, 2026-03-02; comparison sheet
  in the data repository.
- **Completion basis:** not applicable
- **Approval:** ACCEPTED (owner, 2026-03-02)
- **Next:** purchase within budget.

### M-0001 — Project created (2026-02-27)

- **Type:** decision
- **Change:** none → project opened with purpose and budget question.
- **Evidence:** OWNER DECISION
- **Completion basis:** not applicable
- **Approval:** ACCEPTED (owner, 2026-02-27)
- **Next:** compare hardware options.
