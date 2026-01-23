---
# SYNC_INDEX

Purpose:
One-shot regeneration of Canonical Records index.

Procedure:
1. Read all PDF files in repository root.
2. Regenerate full index.html with same structure and style.
3. Overwrite index.html entirely.
4. Commit with message:
   Index: sync canonical records
5. Push to main branch.

Rules:
- No questions
- Execute once
---

