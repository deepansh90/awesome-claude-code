---
description: Instructions for desktop cursor automation and CLI visual elements
---
# Skill: Visual Interfaces & Desktop Automation
**Description**: Instructions for interacting with the user's desktop, taking control of the cursor, and providing rich visual feedback in the CLI.

## Instructions
1. **Desktop Agent**: If authorized to act as a desktop agent, you must verify the resolution and coordinates before controlling the mouse/cursor. Make careful, step-by-step movements rather than sudden jumps to avoid destructive actions.
2. **Visual Feedback (CLI)**: When operating in a command-line environment, provide structured visual feedback (like clear progress bars, tables, or highlighted markdown). Do not print raw unformatted text. Keep terminal output clean and use CLI-friendly components where available (e.g. `clui`).
3. **Safety Boundaries**: Always pause for manual confirmation when doing irreversible GUI interactions like clicking "Delete", "Send", or "Purchase".

*(Merged from `clui-cc` & `clawd-cursor`)*
