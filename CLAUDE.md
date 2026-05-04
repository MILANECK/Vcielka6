# Superpowers Framework

Skills installed in `.claude/skills/`. Invoke any skill by typing its slash command.

## Available Skills

- **design-principles** (`.claude/skills/design-principles/SKILL.md`) — Enforce design tokens, spacing, typography, color, and component consistency.
  Trigger: `/design-principles`
  When the user types `/design-principles`, invoke the Skill tool with `skill: "design-principles"` before doing anything else.

- **test-driven-development** (`.claude/skills/test-driven-development/SKILL.md`) — Red-green-refactor TDD cycle. Never write implementation before a failing test exists.
  Trigger: `/test-driven-development`
  When the user types `/test-driven-development`, invoke the Skill tool with `skill: "test-driven-development"` before doing anything else.

- **accessibility** (`.claude/skills/accessibility/SKILL.md`) — WCAG 2.1 AA audit and fix. Covers semantic HTML, ARIA, keyboard nav, contrast, and focus management.
  Trigger: `/accessibility`
  When the user types `/accessibility`, invoke the Skill tool with `skill: "accessibility"` before doing anything else.

- **code-review** (`.claude/skills/code-review/SKILL.md`) — Structured review across correctness, security, performance, maintainability, and test coverage.
  Trigger: `/code-review`
  When the user types `/code-review`, invoke the Skill tool with `skill: "code-review"` before doing anything else.

- **performance-audit** (`.claude/skills/performance-audit/SKILL.md`) — Web performance audit covering Core Web Vitals, asset loading, rendering, and runtime.
  Trigger: `/performance-audit`
  When the user types `/performance-audit`, invoke the Skill tool with `skill: "performance-audit"` before doing anything else.

## Project

Static HTML website. Files: `index.html`, `admin.html`, `vcielka_editor.html`, `novinka.html`, `novinky.html`, `skolka.html`, `ppv.html`.
