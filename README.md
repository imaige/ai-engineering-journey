# AI Engineering Journey 🚀

This repository is the canonical learning ledger for a structured transition from engineering fundamentals to production-oriented AI Engineering.

The repository is managed around one rule:

> A topic is not considered mastered because it was read, watched, or practiced once. It is marked `PASSED` only after the required mastery gate is completed.

## Canonical Learning Model

Learning progresses in dependency order:

```text
Engineering Environment
        ↓
Python
        ↓
Git & GitHub
        ↓
Linux
        ↓
SQL / PostgreSQL
        ↓
Software Engineering
        ↓
APIs / HTTP
        ↓
Data Foundations
        ↓
Machine Learning
        ↓
Deep Learning
        ↓
Transformers
        ↓
LLM Engineering
        ↓
RAG
        ↓
Agents
        ↓
Evaluation / Observability
        ↓
Serving / MLOps
        ↓
Portfolio / Production Projects
```

The detailed roadmap is maintained outside this repository by the mentor workflow. This repository stores verified learning artifacts, exercises, tests, projects, and progress evidence.

## Repository Structure

```text
ai-engineering-journey/
├── README.md
├── LEARNING_SYSTEM.md
├── PROGRESS.md
├── .env.example
├── .gitignore
│
├── phases/
│   └── 00-engineering-environment/
│       └── README.md
│
├── exercises/
│   └── README.md
├── tests/
│   └── README.md
├── projects/
│   └── README.md
│
└── notes/
    ├── README.md
    ├── ai/
    ├── git/
    └── python/
```

## Current Status

Current canonical phase:

```text
PHASE 0 — Engineering Environment
Status: IN_PROGRESS
```

Topics already practiced in the current mentorship cycle include:

- terminal and path basics
- Python installation and interpreter checks
- virtual environments
- `pip`, dependencies, `requirements.txt`, and basic `pyproject.toml`
- Python object/reference basics
- VS Code interpreter selection
- debugger basics: breakpoint, Step Over, Step Into, Step Out, Continue
- local Git initialization, staging, diff, commits, and status

These items are recorded as practiced, not automatically as phase-level `PASSED`.

See [PROGRESS.md](PROGRESS.md) for the canonical status.

## Legacy Notes

The existing files under `notes/` are retained because they contain useful historical learning material.

They are **reference material**, not proof of current mastery.

A checkbox or completed topic in an older note does not override the current mastery-gate system. See [notes/README.md](notes/README.md).

## Evidence Policy

A topic may be supported by one or more of:

- explanation in the learner's own words
- practical exercise
- debugging task
- test or quiz
- mini project
- code review
- Git history

The final status is governed by [LEARNING_SYSTEM.md](LEARNING_SYSTEM.md).

## Secret Management

Never commit real secrets.

- real API keys belong in a local `.env`
- `.env` is ignored by Git
- `.env.example` documents required variable names only
- virtual environments and generated Python artifacts are ignored
- internal or sensitive security-environment details must not be committed

## Git Workflow

Typical learning update:

```bash
git status
git diff
git add <files>
git commit -m "docs: document verified topic"
git push
```

Repository changes should reflect actual learning evidence rather than inflated progress.

## Goal

Build strong enough foundations to design, implement, debug, evaluate, and operate real AI systems rather than only reproduce tutorials.
