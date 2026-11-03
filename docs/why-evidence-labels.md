# Why every claim carries an evidence label

AI assistants are very good at sounding sure. That's the problem this kit's
evidence labels solve.

## The failure

You ask an assistant for options. It suggests one. A week later, in a new chat,
a different assistant reads your notes, sees that option written down, and
treats it as the plan. Nobody decided it. It was written down, so it looked
decided.

The same thing happens with work you *reported* doing ("I've set up the
backup") but nobody checked, and with facts that were true in March and quietly
stopped being true. Memory features make this worse, not better: they keep the
words and lose how sure anyone was.

## The fix: say how you know

Every material claim in the repository carries one of six labels:

| Label | Read it as |
| --- | --- |
| `VERIFIED` | Someone checked it against named evidence, on a date. |
| `OWNER DECISION` | The owner chose this. Nothing else makes it a decision. |
| `DOCUMENT CLAIM` | A source says so; nobody has confirmed it. |
| `PROPOSED` | A suggestion, waiting for a yes or no. |
| `UNVERIFIED` | We don't have the evidence. |
| `HISTORICAL` | Was true; don't assume it still is. |

The labels cost a few words per line. In return, any assistant, on any
provider, can tell "we decided this" from "someone suggested this" from "this
was true once", without trusting its own memory or yours.

## Three rules that make the labels work

1. **Only the owner turns a proposal into a decision.** An assistant can't
   promote its own suggestion, however good it is.
2. **A report isn't a check.** "I did it" is recorded as owner-reported until
   someone looks. That's not distrust; it's knowing which things to recheck
   when something breaks.
3. **Keep the conflict.** When two sources disagree, record both and say which
   is more reliable and why. Silently picking one is how wrong facts become
   permanent.

## Labels and types work together

Labels say *how sure*. Types say *what kind*: a decision, a lesson, a gotcha,
an open question. "Gotcha, VERIFIED" is a trap someone actually hit. "Lesson,
PROPOSED" is an idea about what to do differently that nobody has agreed to
yet. Decisions also get IDs (`DEC-001-02`), so later records point to the
decision instead of retelling it, and the retelling can't drift.

## Why not just let the AI remember?

Automatic memory is convenient, and for casual use it's fine. For projects
where a wrong "fact" costs you money or time, it has three gaps: it lives in
one provider, you don't approve what it keeps, and it doesn't record how sure
anyone was. A labelled, owner-approved Git repository closes all three, at the
cost of a short review at the end of each session.

---

See [AGENTS.md](../AGENTS.md) for the full rules and
[the synthetic example project](../projects/PRJ-001/current.md) to see the
labels in use.
