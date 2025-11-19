---
description: 
---

---
type: workflow
description: "Generate technical plans and parallel task graphs."
model: gemini-3-pro
---

## User Input
$ARGUMENTS

## Antigravity Agent Instructions

1. **Read Spec**: Load the active `spec.md`.
2. **Technical Plan**:
   - Create `specs/[feature_name]/plan.md`.
   - Define Tech Stack (Default: Google Cloud Native unless specified).
   - Define Data Models (JSON/Protobuf).
3. **Task Graph (Manager View)**:
   - Create `specs/[feature_name]/tasks.md`.
   - **CRITICAL**: Structure tasks for **Parallel Execution**.
     - Group A: Frontend Agents (UI, Client Logic).
     - Group B: Backend Agents (API, DB).
     - Group C: QA Agents (Test scaffolding).
4. **Output**: Display the **Task Graph Artifact**.