# Agent Instructions

Use this repository to help humans inventory agent exposure.

Read order:

1. `README.md`
2. `checklists/exposure-register-checklist.md`
3. `templates/exposure-register.md`
4. `schemas/exposure-register.schema.json`
5. `docs/source-notes.md`

Allowed tasks:

- Draft an exposure register from user-provided facts.
- Flag missing evidence, vague permissions, and unsafe autonomy.
- Convert a completed Markdown register into schema-shaped JSON.
- Recommend stop rules for publish, send, merge, deploy, delete, purchase, or access-change actions.

Boundaries:

- Do not invent permissions, credentials, source evidence, or incident facts.
- Do not include secrets, cookies, tokens, private URLs, local absolute paths, or customer data.
- Do not recommend bypassing approval for destructive, external, financial, or publishing actions.
- When evidence is missing, say what is missing and name the smallest next check.

Output style:

- Be direct and practical.
- Separate verified facts, assumptions, risks, and next actions.

