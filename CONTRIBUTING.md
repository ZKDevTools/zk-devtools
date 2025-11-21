# CONTRIBUTING.md

Thanks for contributing to Circuit Debugger. This doc explains how to get started, code style, and the PR checklist.

## Getting started

1. Fork the repo and create a branch: `git checkout -b feat/short-description`
2. Make your change. Keep changes small and focused.
3. Commit with a meaningful message. Use conventional commits when possible.
4. Push and open a PR targeting `main`.

## Local dev

* Each package in `packages/` is a workspace. Install at repo root using your preferred package manager.
* Run unit tests in package folder: `npm test` or `yarn test`.

## Code style

* TypeScript: Prettier + ESLint (project config will be added).
* Rust (if used): rustfmt + clippy.
* Keep API compatibility in mind — breakage must be agreed via an RFC.

## PR checklist

* [ ] Tests added/updated for any new behavior
* [ ] Linting and formatting applied
* [ ] Documentation updated (README/docs)
* [ ] Example or fixture added when applicable
* [ ] CI passing (when enabled)

## Issues

* Open an issue for large design changes first.
* Label contributions: `good first issue`, `bug`, `enhancement`.

## Code of Conduct

Add the Contributor Covenant as `CODE_OF_CONDUCT.md` before large outreach. Be respectful and constructive.

Thank you — contributors will be credited in `MAINTAINERS.md`.
