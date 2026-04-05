---
description: Instructions for checking and automating browser interactions via CDP/Playwright
---
# Skill: Web Browser Control
**Description**: Gives AI agents access to control browsers or tap into live Chrome tabs.

## Instructions
1. When asked to interact with a web page, prefer connecting to an already running session if possible, using standard Chrome DevTools Protocol (CDP) tools or Playwright.
2. **Current Tab Strategy**: Query for the currently active tab or session. Pull the HTML/DOM of the current context.
3. **Execution**: If executing new web actions, spawn a headless browser using Playwright/Puppeteer and perform the requested actions (clicks, scraping). Do not guess DOM elements — fetch them down, inspect them, then interact.
4. **Resilience**: Handle web auth smoothly by reusing existing session contexts so you don't stall on login walls whenever possible.

*(Merged from `superpowers` & `chrome-cdp-skill`)*
