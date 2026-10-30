# Gitflow Simulation

A practical demonstration of the Gitflow branching strategy.

## Gitflow Workflow

- main: Production-ready code
- develop: Integration branch
- feature: New feature development
- release: Release preparation
- hotfix: Urgent bug fixes

## Features

- Feature branches and Pull Requests
- Release management and version tagging
- Hotfix workflow
- Reusable pre-commit hook
- GitHub Actions CI

## Pre-commit Hook Setup

Run:

    git config core.hooksPath .githooks

## CI Workflow

GitHub Actions automatically checks Python syntax when code is pushed or a Pull Request is created.

## Technologies

- Git
- GitHub
- Python
- GitHub Actions