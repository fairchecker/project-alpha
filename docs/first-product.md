# First product and open questions

The full ecosystem is a long-term direction. The first product should test whether the central interaction actually helps people learn and retain control while making progress.

## Proposed minimum scope

For one project, provide:

1. An editable brief with artifact goals, optional learning goals, and constraints.
2. An AI conversation with selectable, changeable assistance modes.
3. An optional comparison of responses to a focused question from more than one model or perspective.
4. A simple record of decisions, sources, artifacts, and unresolved questions.
5. A brief, optional reflection at a natural stopping point.
6. A way to inspect and export project records, with clear disclosure of what is stored and sent to providers.

This is a proposed scope, not an implementation plan or a promise of features. A manual or prototype workflow may be enough to test the concept before building integrations.

## Example

A user wants to investigate a small solar-powered sensor and learn how to estimate its energy budget. They record both goals, select **Hint**, and work through an initial estimate with guidance. They then use **Demonstrate** to see a worked example and **Collaborate** to compare assumptions. For a routine documentation task, they switch to **Delegate**. A review highlights differing battery assumptions; the user checks component specifications and records their choice. At the end they optionally summarize what they learned and what still needs testing.

## How to evaluate the idea

Try the workflow with a small number of real projects and ask:

- Can users make useful progress without losing track of why decisions were made?
- Do users understand and change assistance modes when they want to?
- Do optional learning prompts help, or do they interrupt and frustrate?
- Can users identify important uncertainty and inspect supporting evidence?
- Can they resume or export a project without relying on a single chat transcript?
- Are time, cost, privacy, and cognitive effort acceptable?

Use interviews, observation with consent, and voluntary examples of explanation or application. Do not infer learning solely from satisfaction, task completion, or model-generated scores.

## Open design questions

- Who is the first intended user, and what kinds of projects do they undertake?
- What should be stored locally, and what may be sent to external providers?
- How should users inspect, correct, delete, and export their project data?
- When does multi-model review add enough value to justify its cost and latency?
- How should a system adapt without making opaque assumptions about a user's ability?
- What accessibility and interface choices make mode switching natural?
- Which integrations and verification methods are appropriate for the first domain?

Answer these through research and small experiments before committing to a large architecture.
