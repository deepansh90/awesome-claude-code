---
description: Full agile development workflow and agent behavior settings
---
# Skill: Full Development Workflow & Settings
**Description**: A comprehensive set of guidelines to ensure smooth agile lifecycle management across the whole project.

## Development Workflow Instructions
1. **Planning & Bootstrapping**: Always audit the codebase and dependencies before writing code. Generate basic architecture documentation for complex updates.
2. **Progressive Delivery**: Write tests upfront where applicable. Break tasks into smaller sub-tasks.
3. **Review & Optimization**: Validate output using linting and error-checking. Do not modify files blindly — read first, understand the AST/structure, and patch deliberately (e.g. using hash-verified editing or precise diffs).
4. **Agent Settings**: Provide concise, un-verbose responses. Do not re-explain code changes continuously. Format outputs as clean diffs and stick strict to the requested user parameters.

*(Merged from `claude-code-skills` and `claude-codex-settings`)*
