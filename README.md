# Pi Skills

Personal skill library for the [pi coding agent harness](https://github.com/mariozechner/pi-coding-agent).

## Structure

Each skill lives in its own directory with a `SKILL.md` file:

```
<skill-name>/
  └── SKILL.md
```

Skills can be nested under category folders for organization.

## Skills

### AI / SDK
- **ai-sdk** — Vercel AI SDK patterns (generateText, streamText, agents, tool calling, useChat)

### Frontend / UI
- **frontend-design** — Production-grade frontend interfaces, components, and design systems
- **shadcn** — shadcn/ui component management, styling, and composition

### React
- **react-patterns** — React 19 patterns (Server Components, Actions, use(), Suspense, Compiler)
- **react-useeffect** — useEffect best practices and anti-patterns

### TypeScript
- **typescript** — TypeScript performance, compilation, tsconfig, async patterns
- **typescript-advanced-types** — Generics, conditional types, mapped types, template literals
- **typescript-best-practices** — Type-first development, exhaustive handling, runtime validation
- **typescript-expert** — Type-level programming, monorepo management, build performance

### Engineering (Matt Pocock)
- **mattpocock-engineering/diagnose** — Hard bugs and performance regressions
- **mattpocock-engineering/grill-with-docs** — Stress-test plans against documentation
- **mattpocock-engineering/improve-codebase-architecture** — Refactoring and architecture
- **mattpocock-engineering/setup-matt-pocock-skills** — Skill setup helper
- **mattpocock-engineering/tdd** — Test-driven development (red-green-refactor)
- **mattpocock-engineering/to-issues** — Break plans into issues
- **mattpocock-engineering/to-prd** — Create PRDs from conversation context
- **mattpocock-engineering/triage** — Issue workflow management
- **mattpocock-engineering/zoom-out** — High-level planning and strategy

### Productivity (Matt Pocock)
- **mattpocock-productivity/caveman** — Ultra-compressed communication mode
- **mattpocock-productivity/grill-me** — Interview/stress-test user plans
- **mattpocock-productivity/write-a-skill** — Create new agent skills

## Installation

Install as a pi package:

```bash
pi install git:https://github.com/shivanandasai-altir/shivananda-skills
```

For project-local use:

```bash
pi install -l git:https://github.com/shivanandasai-altir/shivananda-skills
```

## Updating

```bash
pi update git:https://github.com/shivanandasai-altir/shivananda-skills
```

## Adding a New Skill

1. Create a new directory: `mkdir my-skill/`
2. Add `SKILL.md` with the skill definition
3. Commit and push:

```bash
cd ~/.agents/skills
git add .
git commit -m "Add my-skill"
git push origin main
```
