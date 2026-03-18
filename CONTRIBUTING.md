# Contributing to Rafters

## License

Public Rafters repositories use **AGPL-3.0** or **MIT** licensing (check the specific repo).

AGPL means:
- You can use, modify, and distribute the code
- If you modify and deploy the code, you must open source your modifications
- Network use counts as distribution (if you run a modified version as a service, you must share the source)

## Getting Started

1. Fork the repository
2. Clone your fork
3. Create a branch for your changes
4. Make your changes
5. Submit a pull request

## Code Standards

- **pnpm only** -- no npm or yarn
- **No `any` types** -- use `unknown` and narrow
- **Biome** for linting and formatting
- **UUIDv7** for all IDs
- **OKLCH** for all color values -- no hex, no HSL
- **Zod** for all external data validation
- **async/await** only -- no `.then()` chains
- Run `pnpm preflight` before submitting

## Pull Requests

- Keep PRs focused on a single change
- Include tests for new functionality
- Reference related issues
- One issue, one PR

## Issues

- Search existing issues before creating new ones
- Use issue templates when available
- Include reproduction steps for bugs
- Be specific about expected vs actual behavior

## Architecture

Rafters is a design intelligence protocol. Before contributing, understand the three layers:

- **What** (Components) -- `packages/ui` with JSDoc intelligence metadata
- **Where** (Tokens) -- `packages/design-tokens` with dependency graph and human override tracking
- **Why** (Decisions) -- do/never patterns, cognitive load scores, trust patterns, accessibility requirements

Read the repo's CLAUDE.md for detailed architecture guidance.
