# AGENTS instructions for this repo

## Project overview

This repository contains small, self-contained HTML tools that run directly in a browser with no build step.

## Code style & architecture

- Every tool is a **single `.html` file**.
- Use plain HTML, CSS, and **vanilla JavaScript**.
- Do **NOT** use React, Vue, Svelte, or any other JS framework.
- Do **NOT** use bundlers or Node-based build tools.
- Keep dependencies minimal; only use CDN-hosted scripts when necessary.
- Prefer inline `<style>` and `<script>` tags in the same file.

## UX constraints

- Optimized for **mobile** first (Android Chrome).
- Layout must work well on narrow screens.
- Buttons and tap targets should be touch-friendly.
- No assumptions about keyboard / mouse shortcuts only.

## Build / run instructions

- There is **no build step**.
- Tools should be usable by opening the `.html` file directly in a browser or via GitHub Pages.

## Footer requirements

Every HTML tool must include a footer with:
1. A link to the source code on GitHub (e.g., `https://github.com/joldie/html-tools/blob/main/FILENAME.html`)
2. The date of last edit in `YYYY-MM-DD` format

Example footer HTML:
```html
<footer class="page-footer">
    <a href="https://joldie.github.io/html-tools/" target="_blank" rel="noopener">Home page</a> · Last updated: YYYY-MM-DD · <a href="https://github.com/joldie/html-tools/blob/main/FILENAME.html" target="_blank" rel="noopener">Source code</a>
</footer>
```

**Important:**
- When creating a new tool, always add a footer with today's date.
- When pushing any change to an existing tool, always update the "Last updated" date in the footer to today's date.

## Boundaries

- Don't introduce backends, servers, or databases.
- Don't add complex tooling (Webpack, Vite, npm scripts, etc.).
- When in doubt, choose the simplest possible browser-native solution.