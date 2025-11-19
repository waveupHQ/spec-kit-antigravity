# Project Constitution

## Article I: The Artifact Mandate
**Agents shall not perform work without a visible Artifact.**
- Every planning step must produce a Markdown Artifact (Plan, Spec, or Checklist).
- Never rely on "chat memory" alone. If it's important, write it to a file.

## Article II: Vision Verification
**Trust but Verify (Visually).**
- When implementing UI, the Agent MUST take a screenshot using the integrated Browser.
- Compare the screenshot to the original requirement/mockup.
- If pixels don't match, the task is incomplete.

## Article III: Agent Independence
**Build for Parallelism.**
- Tasks must be atomic.
- Frontend agents should mock API responses if the Backend agent isn't finished.
- Never block a thread waiting for another agent.

## Article IV: Code Health
- **No Legacy Patterns**: Use modern syntax (e.g., React Hooks, ES6+, Python 3.12+).
- **Self-Correction**: If a test fails, attempt to fix it *once* before asking the user.