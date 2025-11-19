# Antigravity Native Commands

## execute.md
---
description: "Spin up parallel agents to build the feature."
mode: manager
---

## Antigravity Manager Instructions

**ACTIVATE MANAGER VIEW**

1. **Orchestrate**:
   - Parse `tasks.md`.
   - Assign **Group A (Frontend)** tasks to Agent 1.
   - Assign **Group B (Backend)** tasks to Agent 2.
   - *Instruction*: "Execute tasks in parallel. Sync on shared Artifacts (e.g., `api-schema.json`)."

2. **Vibe Coding Loop**:
   - Monitor agent outputs.
   - If an agent gets stuck, auto-debug using search.
   - **Diff Artifacts**: Generate a summary of changes for every completed checkpoint.

3. **Completion**:
   - When all agents report "Done", trigger the `/verify` protocol.
