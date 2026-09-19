# Canonical Progress Tracker

Last canonical state: **PHASE 0 — Engineering Environment PASSED**

## Phase Status

| Phase | Topic | Status |
|---|---|---|
| 0 | Engineering Environment | PASSED |
| 1 | Python Programming | NOT_STARTED |
| 2 | Git & GitHub | NOT_STARTED |
| 3 | Linux | NOT_STARTED |
| 4 | SQL / PostgreSQL | NOT_STARTED |
| 5+ | Advanced roadmap phases | NOT_STARTED |

> Git was used during Phase 0 as an environment/tooling prerequisite. Full Git mastery remains a later dedicated phase.

## Phase 0 Evidence

| Area | Evidence | State |
|---|---|---|
| Terminal basics | `cd`, current directory, relative paths practiced | PRACTICED |
| Python runtime | Python 3.14 installed and executable path verified | VERIFIED |
| Path vs PATH | concept explained and practiced | PRACTICED |
| Virtual environment | `.venv` created, activated, deactivated, interpreter path verified | VERIFIED |
| pip | package installation and package location verified | VERIFIED |
| Dependencies | direct vs transitive dependency concept practiced | PRACTICED |
| requirements.txt | generated with `pip freeze` and reproduced in a clean test venv | VERIFIED |
| pyproject.toml | basic project metadata and dependency declaration practiced | PRACTICED |
| Object/reference basics | names, objects, mutation, shallow copy basics practiced | PRACTICED |
| VS Code | Python extension, project interpreter and terminal integration configured | VERIFIED |
| Debugger | breakpoint, Continue, Step Over, Step Into, Step Out practiced | VERIFIED |
| Local Git | init, status, add, diff, staged diff, commit and log practiced | PRACTICED |
| GitHub remote workflow | clone, origin verification, fetch, pull, local commit, push to `origin/main`, remote verification completed | VERIFIED |
| Phase 0 mastery gate | 91/100 on 2026-09-20 | PASSED |

## Review Notes

Weak points identified during the gate and corrected during review:

- exact virtual-environment creation command is `python -m venv .venv`
- `origin` is the conventional short name for the configured remote repository
- `git add` stages changes, it does not modify the source file
- `path` is a concrete filesystem location, while `PATH` is an executable-search directory list
- module/package terminology needs continued repetition

## Rule

A phase changes to `PASSED` only after its mastery gate reaches at least 90% and the required evidence is present.
