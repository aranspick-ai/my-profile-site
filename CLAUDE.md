# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Status

The only file in this repository is `roadmap.md`, a plan (written in Korean) for building a single-page developer résumé website. No source code, build tooling, tests, or git history exists yet, so there are no build, lint, or test commands to document.

## Planned project (from `roadmap.md`)

- Stack: plain HTML, CSS, and JavaScript. No framework and no build step, so the site is opened directly in a browser (or served as static files) and deployed to GitHub Pages.
- Planned layout: `index.html`, `css/style.css`, `js/main.js`, `assets/`.
- Planned JS features: smooth-scroll navigation, scroll-reveal animation via `IntersectionObserver`, dark-mode toggle persisted in `localStorage`, mobile menu toggle.
- Résumé content is generic placeholder data (profile, contact, intro, skills, projects, experience, education, certifications).

Treat `roadmap.md` as the source of truth for scope. Once code is added, re-run `/init` to replace this section with actual commands and architecture.
