# Project Directory

**Role:** Navigation to each project's master file. This directory does not
replace them.
**Updated:** YYYY-MM-DD

Keep project IDs stable: don't renumber or reuse them, even when a project
closes. An index-only entry (no master file yet) is not permission to access
that project's data.

| ID | Project | Master file | Latest recorded state |
| --- | --- | --- | --- |
| PRJ-001 | Home Office Network Refresh *(synthetic example)* | [Current](PRJ-001/current.md) | Active — mesh installed; cabling pending quote. |
| PRJ-002 | <Your first real project> | Index entry only | Not yet recorded. |
| PRJ-003 | <Example: an idea you dropped> | Index entry only | Closed YYYY-MM-DD — <reason>. |
| PRJ-004 | <Example: work absorbed elsewhere> | See PRJ-002 | Merged into PRJ-002 YYYY-MM-DD; ID kept. |

## Load summary (YYYY-MM-DD)

Active: PRJ-001. Waiting: PRJ-002. Closed: PRJ-003. Merged: PRJ-004 into
PRJ-002.

## Keeping the register tidy

- **Close** projects you've stopped, with the date and reason. Don't delete
  the row.
- **Merge** overlapping projects into one, and keep the merged ID pointing to
  its new home so old references still resolve.
- **Combine** projects that must move together into one stream (for example
  "PRJ-005 and PRJ-006 run as one stream") instead of tracking them twice.
- Refresh the load summary whenever a state changes, so the whole picture is
  one line.

## Using the directory

Open the project's `current.md` (or `overview.md` if it has none) at the
current Git revision, and longer records only when needed. Original data stays
in each project's folder in the data repository.
