# Decision Capture Prompt

```text
Identify whether the current discussion produced a significant project decision.

A decision is significant if it changes:
- Architecture.
- Project direction.
- Technical dependencies.
- Scope.
- Constraints.
- Future implementation.

If significant, propose saving it using:

## [Date] — [Decision]
- Rationale:
- Alternatives:
- Evidence:
- Unverified assumptions:
- Conditions for reconsideration:

Do not save without user approval unless automatic decision capture is explicitly enabled.
Do not rewrite historical decisions.
```
