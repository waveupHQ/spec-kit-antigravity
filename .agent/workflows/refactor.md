---
description: Clean up legacy code before feature work.
---

## User Input

$ARGUMENTS

## Instructions

1. **Audit**: Scan the target directory `$ARGUMENTS`.
2. **Constitution Check**: Compare against `/memory/constitution.md`.
3. **Refactor**: Apply modern patterns (e.g., "Convert Promises to Async/Await") WITHOUT changing business logic.
4. **Verify**: Run existing tests to ensure no regression.