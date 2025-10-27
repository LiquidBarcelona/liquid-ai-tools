# TEAM AI Tools

This repository contains internal AI tools, scripts, and guidelines for our development team. Its purpose is to **improve productivity, code quality, and consistency** when working on Laravel and PHP projects, using AI-assisted code generation tools safely and effectively.

---

## 📌 Purpose

- Provide a centralized place for AI-assisted development workflows.
- Define **coding standards and guidelines** for AI-generated code.
- Share reusable scripts, templates, and utilities for the team.
- Ensure all AI-assisted code remains **readable, maintainable, and backward compatible**.

## 📥 Installing the TEAM AI Guidelines for Claude

To make Claude follow our internal Laravel & PHP coding standards, follow these steps:

```bash
# 1. Ensure the Claude configuration file exists
touch CLAUDE.md

# 2. Download the TEAM AI Guidelines from our repository
curl -o laravel-php-guidelines.md https://raw.githubusercontent.com/LiquidBarcelona/liquid-ai-tools/master/liquid-ai-laravel-guidelines.md

# 3. Tell Claude to read the guidelines file
echo -e '\n## Coding Standards\nWhen working on this Laravel/PHP project, first read the coding guidelines at @laravel-php-guidelines.md' >> CLAUDE.md
