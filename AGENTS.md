# TeksTrader Public Repository Guidelines

## Purpose

This public repository is the project-facing home and website source for TeksTrader. It contains public information and does not contain application source code.

## Public Content

Use this repository for:

- The project README
- The static website under `docs`
- Approved marketing copy
- Published application links
- Issue templates and issue tracker configuration
- Public support and contribution information

Confirm product claims, links, availability, prices, support policies, and security statements with the user before publication. Do not infer them from private code.

## Privacy

Do not add internal specifications, implementation plans, private architecture, credentials, operational details, or unreleased behavior to this repository.

Describe only released behavior and information that the user approves for publication. Remove private details from issue examples, logs, screenshots, and copied error messages.

Do not mention any private repository or its name in this repository.

## Change Scope

Make the smallest change that fully satisfies the requirement. Do not include unrelated rewrites, formatting, policy changes, or generated files.

Reuse existing text and templates when they fit. Do not duplicate guidance across public files.

## Version Changelog

The frontend and backend use independent Semantic Versioning numbers.

Create or update `CHANGELOG.md` for every frontend or backend major or minor release. Identify the component and full release version in each entry.

Do not add changelog entries for patch-only releases. Patch versions identify non-production deployments.

## Documentation Style

Write concise Markdown in clear American English. Use descriptive link text and stable headings. Keep product terminology consistent across the README and issue templates.

Do not add badges, legal terms, contribution policies, codes of conduct, or security policies without user approval. Check every external link before you publish it.

## GitHub Pages

GitHub Pages publishes `docs` from the `main` branch at `https://tekstrader.com`.

Keep the site as plain static HTML until the user approves a different toolchain. Do not add a framework, generator, package manager, dependency, or custom Pages workflow without approval.

Keep `docs/CNAME` set to `tekstrader.com`. Keep public site assets under `docs/assets` and use relative paths within the site.

Publish only approved public information. Do not infer website claims from private code, plans, specifications, or operations.

## GitHub Wiki

GitHub stores the wiki in a separate Git repository. Do not create a local wiki directory or duplicate wiki pages here unless the user requests it.

## Validation

Use the repository's configured HTML, Markdown, and link checks when they exist. Until then, review site paths, headings, links, public claims, and privacy.