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

## Boundaries

- Don’t introduce backends, servers, or databases.
- Don’t add complex tooling (Webpack, Vite, npm scripts, etc.).
- When in doubt, choose the simplest possible browser-native solution.