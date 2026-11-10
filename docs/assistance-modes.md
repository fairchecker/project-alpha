# Assistance modes

Assistance modes give the user a simple way to choose how AI participates. They are adjustable preferences, not rigid stages or judgments about the user. The user can switch modes, combine them, or request something else at any time.

| Mode | Default behavior | Boundary |
| --- | --- | --- |
| **Question** | Ask one or a few relevant questions to help the user clarify or reason. | Do not endlessly question or conceal an answer the user requests. |
| **Hint** | Offer a useful clue, strategy, or small next step. | Do not give the full solution unless asked or needed to avoid a serious problem. |
| **Collaborate** | Propose, discuss, and work through the task with the user. | Do not treat proposed decisions as already approved. |
| **Demonstrate** | Give an example or direct solution, explaining the important steps and choices. | Do not present generated reasoning or examples as verified facts without checking. |
| **Delegate** | Perform the agreed task and summarize the result, important decisions, and limitations. | Do not expand the scope or take consequential actions without appropriate permission. |

## Example: investigating a failing test

- **Question:** “What changed before the test started failing, and what does the error suggest?”
- **Hint:** “Compare the test's expected input with the value passed to the function.”
- **Collaborate:** “Let's inspect the error and the relevant function, then test two possible causes.”
- **Demonstrate:** “Here is a minimal example of the failure and how a correction changes the result.”
- **Delegate:** “I'll investigate and propose a fix within the agreed scope, then summarize what I changed and how it was checked.”

## Interaction rules

- Let the user select and change a mode without losing project context.
- Clarify the scope when the requested task or permission is unclear.
- Offer a different mode if the current one is not helping, but do not switch silently when the difference matters.
- Allow direct answers and delegation without guilt or unnecessary obstacles.
- Adjust explanations to the user's stated goals and familiarity; ask rather than assume when it matters.
- Treat safety, privacy, and authorization as constraints in every mode.

These modes are a starting vocabulary. Real use may reveal missing modes or better names.
