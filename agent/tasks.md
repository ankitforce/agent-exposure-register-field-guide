# Agent Tasks

## Draft An Exposure Register

Input: user-provided description of an agent, product, workflow, or automation.

Output:

- Verified facts
- Missing facts
- Draft exposure register
- Stop rules
- Smallest next checks

## Audit A Register

Input: completed Markdown or JSON register.

Output:

- High-risk exposure
- Missing evidence
- Approval gaps
- Memory and persistence gaps
- Recommended changes

## Convert Markdown To JSON

Input: `templates/exposure-register.md` filled by a human.

Output: JSON matching `schemas/exposure-register.schema.json`.

