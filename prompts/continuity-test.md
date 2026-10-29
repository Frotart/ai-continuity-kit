# Continuity test prompt

Run this with each assistant you use (in a fresh chat, with no prior context) to
check that your repository alone is enough to resume a project. If an assistant
fails a criterion, improve the records rather than the prompt.

---

> **Continuity test — read-only.**
> Repository: `<owner>/<repo>`. Use authenticated read access. Do not rely on
> previous conversations, memory or web search as a substitute for the
> repository. Make no changes anywhere.
>
> 1. Report the current default-branch commit SHA and how you obtained it.
> 2. Read `README.md`, `AGENTS.md`, both policies, `projects/index.md`, and the
>    overview and status of `<PRJ-NNN>`.
> 3. Explain the project's purpose and where its source-of-truth boundaries lie
>    (what lives in Git versus the data repository).
> 4. List its current decisions, separating owner decisions, verified facts,
>    document claims and proposals.
> 5. Identify open gates, unverified claims, stale information and the next safe
>    action.
> 6. Confirm that you made no changes and disclosed nothing outside this chat.
>
> Grade each step **PASS**, **PARTIAL**, **FAIL** or **BLOCKED**, citing the
> file and section you relied on. If you cannot access the repository, report
> BLOCKED and do not guess its contents.

---

**What good looks like:** the assistant names the exact commit, keeps evidence
labels intact, doesn't upgrade a proposal into a decision, and proposes a next
step that needs no new permission.
