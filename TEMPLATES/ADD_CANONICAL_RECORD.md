---
# ADD_CANONICAL_RECORD

Purpose:
One-shot addition of a Canonical PDF and synchronized index update.

Execution Rules:
- Do not ask questions
- Do not split steps
- No human intervention
- Execute once, end

Tasks:

1. Add the following file to the repository root as a Canonical Record:
   【PDF文件名.pdf】

2. Do not rename, modify, or replace any existing PDF.

3. Commit the addition with the exact message:
   Add Canonical Record: 【PDF文件名】 (YYYY-MM-DD)

4. Read index.html and regenerate a complete version,
   without changing structure, styles, or scripts,
   listing the new PDF under Records / Standards.

5. Overwrite index.html entirely (no line insertion).

6. Commit the index update with the exact message:
   Index: list 【PDF文件名】

7. Push to main branch.
---

