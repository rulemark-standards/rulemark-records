---
# SYNC_INDEX

Purpose:
One-shot synchronization of Canonical Records index.

Tasks:

1. Read all PDF files in the repository root.
2. Read index.html.
3. Regenerate a complete index.html,
   without changing structure, styles, or scripts,
   listing all PDFs under Records / Standards.
4. Overwrite index.html entirely.
5. Commit with the exact message:
   Index: sync canonical records
6. Push to main branch.

Rules:
- No questions
- No manual editing
- Execute once
---

