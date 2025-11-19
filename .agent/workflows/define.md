---
description: "Create a rigorous feature specification using Gemini 3's reasoning."
model: gemini-3-pro
---

## User Input

$ARGUMENTS

## Antigravity Agent Instructions

1. **Ingest Context**: Read `/memory/constitution.md` and scan the repo.
2. **Vision Analysis**: If images were uploaded, analyze them for UI components, layout, and flow.
3. **Draft Spec**:
   - Create `specs/[feature_name]/spec.md`.
   - Use the template at `templates/spec.md`.
   - **Auto-Correction**: If the user asks for something that violates the Constitution (e.g., "messy code"), correct it and note the correction.
4. **Interactive Reasoning**:
   - Identify _Functional Gaps_ (what happens if X fails?).
   - Identify _Edge Cases_.
5. **Output**: Display the **Spec Artifact**.
