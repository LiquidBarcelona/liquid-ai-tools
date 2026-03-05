# Development Philosophy

## Divide and Conquer: Iterative Development

- Break down features into **small, testable iterations**
- Test each step before moving forward
- Avoid ambitious multi-change approaches that can break everything
- Build small, reusable functions that work perfectly

## Backend Development (TDD Approach)
1. Write a **simple test** first
2. Implement the minimal code to pass it
3. Verify it works before continuing

### Test Guidelines
- Keep tests simple and focused
- Check what matters (e.g., status code 400)
- Skip unnecessary assertions (e.g., exact error message text)

## Frontend Development (HTML/CSS)
- **No unit testing required** for UI
- Start minimal: something that works and looks decent
- Iterate and improve the interface gradually
- **Follow existing HTML patterns** in the project
- Keep it simple, avoid over-engineering from the start

## Coding Standards
When working with Laravel/PHP projects, first read the coding guidelines at @~/.claude/laravel-php-guidelines.md

## Output
When finishing a task, provide a **short summary** similar to a concise git commit message.
Avoid long explanations or recaps of things we've already discussed or iterated on.

## Writing Style

Maintain a clear and professional style without relying on generic, grandiose, or AI-like expressions. Prioritize precise and natural wording, avoid exaggerations or prefabricated phrases, and steer clear of any language that might feel artificial or repetitive. When writing reports, avoid titles such as “Executive Summary,” redundant conclusions, or other formulaic sections. Also avoid unnecessary emoticons or emojis.
