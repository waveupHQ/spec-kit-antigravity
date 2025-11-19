# 🚀 Spec Kit for Google Antigravity

**Build software at the speed of thought.** This kit adapts [Spec-Driven Development](https://github.com/github/spec-kit) for **Google Antigravity**, leveraging the native `.agent` workflow engine.

## ⚡️ Quick Start

1. **Clone this repo** into your workspace.
2. **Antigravity** will automatically detect the `.agent/workflows` directory.
3. **Start Vibe Coding**:

| Workflow | Phase | Description |
| :--- | :--- | :--- |
| **`/define`** | **Spec** | Drag in screenshots/sketches. Gemini 3 creates a rigorous spec. |
| **`/architect`** | **Plan** | Generates technical plans & parallel task graphs for Manager View. |
| **`/execute`** | **Build** | Spins up independent agents to build Frontend & Backend in parallel. |
| **`/verify`** | **QA** | Visual regression & logic testing using the integrated Chrome browser. |
| **`/refactor`** | **Cleanup** | Audits and refactors legacy code per constitution before adding features. |

## 🧠 The Core Philosophy

* **Artifacts over Logs**: We don't read chat logs. We review generated Artifacts (Specs, Plans, Checklists).
* **Vision First**: Specs shouldn't just be text. Use Antigravity's vision to "see" the design.
* **Manager Mode**: Don't serial-code. Use `/execute` to run multiple agents at once.

## 🛠️ Integrating Spec Kit into an Existing Project

1. **Copy the kit's core folders** into your project root:

   ```bash
   cp -r /path/to/spec-kit-antigravity/.agent .
   cp -r /path/to/spec-kit-antigravity/memory .
   cp -r /path/to/spec-kit-antigravity/templates .
   ```

2. **Calibrate the Constitution** (`memory/constitution.md`) to reflect your project's tech stack, style guide, and forbidden patterns.

3. **Bootstrap a baseline spec** (Reverse Spec):
   - Open the Antigravity chat (Manager View).
   - Run: `/define Create a baseline spec for the existing authentication module in src/auth.`

4. **Add new features** using the usual flow:
   - `/define …` → `/architect` → `/execute` → `/verify`.

5. (Optional) **Run the Refactor workflow** on legacy modules before adding features:
   - `/refactor src/legacy_module`

