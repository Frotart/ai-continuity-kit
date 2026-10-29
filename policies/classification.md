# Knowledge Classification and Admission

**Purpose:** Let useful project knowledge be shared with the assistants you
authorize, while keeping confidential material out of the repository.

## Classes

| Class | Definition | Admission |
| --- | --- | --- |
| Public | Suitable for anyone to read | Eligible after an accuracy and rights check |
| Internal | Non-public, low-sensitivity working knowledge | Eligible with explicit owner approval of the content |
| Confidential | Personal, commercial, operational or academic information that needs protection | **Excluded** — stays in the data repository |
| Restricted | Credentials, authentication data, recovery secrets | **Strictly excluded** — use a password manager |

If you're unsure which class something is, it doesn't go in until it's reviewed.
A private repository does not make confidential material safe to store: it is
still hosted by a third party and readable by every connected assistant.

## Eligible content

- Approved project objectives, scope and architectural direction.
- Working instructions and source-of-truth rules.
- Project status, with evidence labels and limitations.
- Decision references, open gates and lessons learned.
- Synthetic examples clearly marked as non-operational.
- Small scripts and technical notes that contain no secrets or real data.
- **Pointers** to original documents (title or folder), not their contents.

## Always excluded

- Records about other people: customers, candidates, employees, students.
- Confidential business, legal or academic documents and their detailed
  summaries.
- Financial transactions, payroll, banking or production datasets.
- Passwords, API keys, tokens, cookies, recovery codes, credential exports.
- Raw chat transcripts and full AI memory exports.
- Installers, binaries, bulk datasets, backups and machine inventories.
- "Sanitized" summaries whose conclusions are still confidential.

Information can be sensitive in combination even when each fact looks harmless.

## What a proposed addition must state

1. Exact path and content.
2. Source or factual basis.
3. Classification, and why nothing more sensitive is included.
4. Which assistants or people will be able to read it.
5. For material facts: how they were verified, and when.
6. The owner's approval of that exact version.

## Disclosure is a separate decision

Approving content for this repository does not approve sending it to a new AI
provider, connector or person. Each new destination needs its own approval of
the content, recipient and purpose.

## If something inadmissible gets in

1. Stop further copying or sharing.
2. Restrict access if needed.
3. Check history, forks, clones and anything already shared.
4. Get the owner's authorization for clean-up, then verify it.

Deleting a file does not remove it from Git history or from copies already made.
Rotate any exposed secret immediately.

## Limits

This policy describes intended behaviour. Repository permissions, connector
settings and device security must be checked separately.
