# Multi-model review

Different models and perspectives can expose alternatives and blind spots. They can also repeat the same errors, share training biases, or produce confident but unsupported claims. The purpose of review is better-informed judgment, not a majority vote.

## A practical process

1. **Frame a focused question.** Provide the same relevant project context and constraints to each reviewer. Remove sensitive information unless sharing it is appropriate and authorized.
2. **Gather initial perspectives independently.** For important questions, avoid showing one response to the others before they form an initial view. This reduces anchoring but does not guarantee independence.
3. **Ask for structured answers.** Request a recommendation, assumptions, supporting evidence or sources, limitations, and what might change the recommendation. Ask reviewers to label speculation and avoid invented citations.
4. **Compare claims, not personalities.** Identify where responses agree, differ, or answer different questions. Note whether differences come from evidence, assumptions, priorities, or uncertainty.
5. **Check important claims.** Consult primary sources or run appropriate experiments where feasible. Record what was actually checked and what remains unverified.
6. **Present the result to the user.** Preserve consequential disagreements and the strongest reasons on each side. Identify decisions the user needs to make and possible next tests.

Using multiple models may cost more, take longer, and expose data to additional providers. It should be optional and proportional to the decision.

## Possible perspectives

These can be prompts, people, or models; separate roles do not imply independent evidence.

- **Proposer:** develops candidate approaches.
- **Critic:** challenges assumptions and identifies failure modes.
- **Evidence reviewer:** checks whether claims are supported and sources are relevant.
- **Learning reviewer:** identifies concepts or decisions worth understanding.
- **Practitioner:** considers feasibility, maintenance, and constraints.

## Review summary template

```text
Question and context:
Perspectives consulted:
Agreements and their basis:
Disagreements and their basis:
Evidence checked and sources:
Unverified claims and limitations:
Options and tradeoffs:
Suggested next experiment or decision:
User's decision and reasons:
```

## Prompt for independent proposals

> Review the following project question and context. Propose an approach, state your assumptions, identify relevant evidence and limitations, and explain what could change your recommendation. Separate verified facts from inference and speculation. Do not invent sources. Include learning opportunities and risks, but respect the user's time and agency.

## Prompt for synthesis

> Compare these responses claim by claim. Preserve meaningful disagreement and explain whether it comes from evidence, assumptions, or priorities. Identify unsupported claims and questions requiring verification. Do not treat agreement among models as proof. Present options and tradeoffs for the user rather than making the final decision for them.
