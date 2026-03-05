# Global Instructions

## Environment

Multi-project workspace (~100+ projects). Primary stack: Laravel/PHP, Craft CMS, Vue.js. Each project lives in its own directory with its own `CLAUDE.md`.

## How I Work

- Break features into small, testable iterations. Test each step before moving forward.
- Backend: write a simple test first, implement minimal code to pass it, verify before continuing.
- Frontend: no unit tests for UI. Start minimal, iterate gradually. Follow existing HTML patterns in the project.
- HTML: prefer native semantics over ARIA patches. HTML first, CSS second, JS last.

## Verification

- Backend changes: run the relevant test suite before considering a task done.
- Frontend changes: verify the page renders correctly.
- Always check for regressions in related functionality.

## Coding Standards

- Laravel/PHP projects: read `~/.claude/laravel-php-guidelines.md` first.
- Deploy scripts and server tasks: follow `~/.claude/sysadmin-guidelines.md`.

## Output

When finishing a task, provide a short summary similar to a concise git commit message. No long recaps.

## Writing Style

Clear and professional. No generic AI expressions, no grandiose language, no prefabricated phrases. No emojis. In reports, skip formulaic sections like "Executive Summary" or redundant conclusions.
