# self-review

An agent skill that makes an AI agent check its own work before it delivers anything.

## The loop
1. Read the lessons file and the last result of the same job.
2. Size the task: light, normal or high-stakes.
3. Research facts from primary sources and label each claim FACT, INFERENCE or NOT VERIFIED.
4. Draft, critique against the ask, role, facts, proof, voice and next step, then revise the whole draft.
5. For high-stakes work, get one round of second review (PASS or a numbered fix list).
6. Stay inside the caps: at most 2 loops and 1 review round.
7. After delivering, log one dated lesson, and turn human corrections into standing rules.

## Install
Copy `SKILL.md` into your agent's skills folder, for example `skills/self-review/SKILL.md`. Agents that support skills pick it up from the `name` and `description` in its frontmatter.

## License
MIT © 2026 Armstrong Kiprotich
