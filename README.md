# Learning-Centered AI Research and Development

An open framework for researching, learning, and building with AI—where the user's understanding and agency matter alongside the quality of the result.

> The goal is not simply to produce an answer. It is to make progress in a way that leaves the user better able to understand, evaluate, and extend the work.

This repository is an early starting point for a future ecosystem and tool. It contains principles, workflows, and open design questions—not a finished product or a claim that the approach has been validated.

## Why this exists

AI can accelerate research and development, but speed alone is a narrow measure of success. A system can produce a convincing answer while obscuring assumptions, making decisions for the user, or leaving them unable to judge the result.

We want an alternative: AI that helps people make useful things **and** develop their own capabilities. Sometimes that means asking a question or offering a hint. Sometimes it means explaining an example, collaborating, or doing a task on the user's behalf. The important thing is that the choice is intentional and remains with the user.

## What we are trying to build

A workspace for projects that connects:

- **Goals:** what the user wants to make, investigate, or decide—and what they want to learn.
- **Adjustable assistance:** different modes of AI help, from questions and hints to direct delegation.
- **Research and experimentation:** sources, assumptions, hypotheses, tests, and results.
- **Multiple perspectives:** structured input from different models or roles, without treating agreement as proof.
- **Decisions and artifacts:** a visible record of what was made, chosen, and why.
- **Reflection:** lightweight opportunities to notice progress, understanding, and remaining uncertainty.

The user should be able to move between these activities rather than follow a rigid sequence.

## Assistance modes

| Mode | AI's role | Useful when |
| --- | --- | --- |
| **Question** | Ask focused questions that help the user think. | The user wants to explore or frame a problem. |
| **Hint** | Offer a clue or next step without giving away the whole solution. | The user wants to practice. |
| **Collaborate** | Work through an idea or task together. | The user wants an active partner. |
| **Demonstrate** | Show an example or solution and explain important reasoning. | The user wants to see how something works. |
| **Delegate** | Carry out an agreed task and provide a reviewable result. | The user wants to move past a task or save time. |

These are options, not levels the user must progress through. The user can switch at any time, ask for a direct answer, or define a different mode. See [Assistance modes](docs/assistance-modes.md).

## A typical loop

1. **Orient:** define the project, learning goals, and constraints.
2. **Map:** identify concepts, assumptions, alternatives, and unknowns.
3. **Explore:** investigate with the level of assistance the user chooses.
4. **Compare:** examine relevant perspectives, evidence, and disagreements.
5. **Decide and experiment:** choose a small next step and make its purpose clear.
6. **Build and review:** carry out the work and inspect its results.
7. **Reflect:** capture useful lessons and choose what to do next.

This is a loop, not a mandatory checklist. See [Workflow](docs/workflow.md).

## Read the documents

- [Core principles](docs/principles.md) — values and design commitments.
- [Assistance modes](docs/assistance-modes.md) — how the user controls AI participation.
- [Workflow](docs/workflow.md) — a practical research and development loop.
- [Multi-model review](docs/multi-model-review.md) — comparing perspectives without manufacturing certainty.
- [First product and open questions](docs/first-product.md) — a small starting scope and what needs validation.

## Current status and next steps

This is a conceptual foundation. No application, model integration, or evaluation results are included yet.

The next step is to gather independent critiques of these documents, compare their assumptions and disagreements, and test a small workflow with real users and projects. The documents should change when experience or evidence suggests a better approach.
