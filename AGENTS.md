> Keep this file current as the docs structure, product names, or writing rules change.

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "docs" or "documentation site" for this repository.
- Use product names exactly as branded: "PaperGravity", "ParkSig", and "Pixlayo".
- Use "dashboard" for the customer application when referring to product access.
- Use "account" for a customer's login or tenant access unless a page already defines a more specific term.
- For ParkSig, prefer "parking sign permit" or "permit" over generic terms like "record".
- For Pixlayo, prefer "asset" for uploaded visual content.

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Keep product descriptions factual. Do not add marketing copy.
- Start procedural pages with prerequisites when setup or permissions matter.
- Prefer short sections, steps, and cards over long prose blocks.
- Match the existing naming used in navigation and page titles.

## Content boundaries

- Document customer-facing PaperGravity docs for ParkSig and Pixlayo.
- Do not document internal-only operations, admin tooling, or implementation details unless the repo already exposes them in public docs.
- Keep content focused on setup, usage, troubleshooting, and API-facing behavior.
- When updating navigation or product structure, verify changes in `docs.json`.
