# Build and Run

The source repository for Dylan W. Lim Portfolio Site remains private. The notes below are safe public-level orientation for people with source access.

## Local development

- Use npm for dependencies.
- Install with npm install.
- Run npm run dev for local development.
- Run npm run build for production build validation.
- Use lint, typecheck, Playwright, and Lighthouse checks from the private repository when making source changes.

## Validation

Use the private repository's documented validation scripts before publishing or deploying source changes. For documentation-only work, verify links, file names, and public-safe language before publishing.

## Public docs publishing

The private source repository contains a docs-only publish workflow. It copies allowlisted Markdown files from `docs-public/` into this public documentation repository and runs a leak check before publishing.
