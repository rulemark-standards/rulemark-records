---
# ADD_CANONICAL_RECORD

Purpose:
One-shot addition of a Canonical PDF and synchronized index update.

Rules:
- Use the original PDF filename automatically
- Do not ask questions
- Do not split steps
- Execute once

Procedure:
1. Detect newly added PDF(s) in repository root.
2. Add them as Canonical Records without renaming.
3. Commit with message:
   Add Canonical Record: <PDF filename> (YYYY-MM-DD)
4. Regenerate a complete index.html listing all PDFs.
5. Overwrite index.html entirely.
6. Commit with message:
   Index: sync canonical records
7. Push to main branch.
---

