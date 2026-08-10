# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Status

This repository (`ugc-workflow`) is currently empty — it contains no source code, build configuration, tests, CI workflows, or documentation other than this file. Last verified: August 2026.

Because there is no code yet, there are no build/lint/test commands to run and no architecture to describe. Do not assume any tooling, language, or framework exists until it is actually added to the repository.

## Working in This Repository

- When adding the first code, choose tooling explicitly (language, package manager, test runner, linter) and document those choices in this file in the same change.
- Keep this file accurate: it should describe what is actually in the repository, not aspirations.

## Guidance for Future Updates

As code is added, update this file to include:

- **Commands**: how to install dependencies, build, lint, run tests (including a single test), and run the application.
- **Architecture**: the high-level structure and how major pieces fit together — anything that requires reading multiple files to understand.
- **Conventions**: project-specific patterns, naming, or workflow rules that are not obvious from the code itself.
