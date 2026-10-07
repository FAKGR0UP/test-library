# test-library

Markdown test fixtures for the next-library documentation pipeline.

## Overview

A content-only repository (it has no `package.json`). It holds Markdown files
under `api/`, `examples/`, `getting-started/`, `guides/` and `i18n/`, where
`i18n/` contains per-locale copies (for example `af`, `ar`, `az`).

Several file names, such as `invalid-markdown.md`, `malformed-frontmatter.md`,
`missing-file.md` and `empty-file.md`, suggest that the set is meant for testing
edge cases in the docs pipeline.

## Contents

- `getting-started/`: installation and first-steps pages.
- `guides/`: beginner and intermediate guides, including `core-concepts/` and `advanced-configuration/`.
- `api/`: API reference pages.
- `examples/`: basic and real-world example pages.
- `i18n/`: translated copies of the pages, one folder per locale.
