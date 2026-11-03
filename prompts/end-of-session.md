# End-of-session prompt

Paste this at the end of a working session so the repository, not the chat,
carries the work forward. It turns the session into one reviewed change.

---

> **End of session — draft only, commit nothing yet.**
> Repository: `<owner>/<repo>`, current default branch.
>
> 1. Report the commit SHA you are drafting against.
> 2. From **this conversation only**, list each project touched (PRJ-NNN) and,
>    for each: decisions I made (with date and the next `DEC-NNN-NN` ID),
>    lessons and gotchas worth keeping, things verified (evidence, date),
>    things I reported doing that nobody checked, proposals not yet accepted,
>    and the next concrete step. Skip parts of the chat I marked curiosity,
>    fun or "off record", unless I said "log that". If nothing material
>    changed, say so and stop.
> 3. Draft updates to each touched project's `current.md` and to `today.md`.
>    Keep each file's layout, label every fact, never upgrade an owner report
>    to VERIFIED, and end `current.md` with an opener line for the next
>    session.
> 4. Only if a project's one-line state in `projects/index.md` is now wrong,
>    draft that row too.
> 5. Before showing me anything, remove credentials, account numbers, amounts,
>    other people's details, raw chat text and anything that belongs in the
>    data repository.
> 6. Show a plain-language summary per file plus the diff, then ask once for
>    approval. Commit and push only if my reply clearly covers pushing
>    ("approve and push"). "Looks good" accepts the content, not the push.

---

**Why it matters:** a session that ends without this step leaves its decisions
in one provider's chat history, which is exactly what this kit exists to avoid.
