# Sumit

**Software engineer. I design and build systems where the trade-offs are the interesting part.**

I like breaking hard problems down: working out what a system should guarantee, what it can't, and writing code that is honest about the difference.

---

## Selected work

### [SimplyDone4J](https://github.com/learnerview/SimplyDone4J)
A Redis-backed distributed job scheduling library.

- Priority scheduling, retries, and idempotent execution
- Leases to detect stalled workers, with fencing tokens so a worker that comes back late can't overwrite newer work
- Built around one question: **what execution guarantees can a job scheduler actually provide when workers crash, pause, or lose their lease?**

### [ARARE](https://github.com/projectARARE/ARARE)
Constraint-based university timetable scheduling.

- Models timetabling as a constraint problem
- Partial re-solving: identify the sessions affected by a change and re-optimize that portion while preserving unaffected sessions
- Disruption impact analysis to show what a change touches before it is applied

---

## How I work

- Start from the failure modes, then design the happy path
- Prefer simple mechanisms I can reason about over clever ones
- Pick the tool that fits the problem, not the other way around

---

## Problem solving

| Platform | Peak |
|---|---|
| LeetCode | 1955 (Knight) |
| Codeforces | 1351 (Pupil) |
| CodeChef | 1633 (3★) |

---

## Contact

[GitHub](https://github.com/learnerview) · [LinkedIn](https://www.linkedin.com/in/learnerview/)
