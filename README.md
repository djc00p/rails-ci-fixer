# rails-ci-fixer

[![ClawHub Skill](https://img.shields.io/badge/ClawHub-Skill-blue)](https://clawhub.ai/djc00p/skills/rails-ci-fixer)

Fix failing CI on Rails PRs using a tiered escalation loop. Use this skill whenever a Rails pull request has failing CI — RSpec failures, RuboCop offenses, migration errors, factory issues, seed data problems, or build environment failures (yarn, npm, Tailwind, missing system deps). Fix, verify, then pause for human approval before committing. Pull logs, fix with a fast model, escalate to a stronger model if needed, notify human when green or stuck. Never merges — human always merges. Trigger phrases: fix CI, CI is failing, CI is red, watch the PR, fix the tests, the build is broken.

---

## Install

Install from ClawHub:

```bash
clawhub install rails-ci-fixer
```

Or clone this repo and add the skill folder to your agent's skills path.

## Usage

This skill activates automatically when a request matches its description.
See `SKILL.md` for the full instructions the agent follows.

## Repository layout

```
SKILL.md      # agent instructions
LICENSE       # MIT-0 / MIT
README.md     # this file
```

## Versions

Releases track the published ClawHub versions.

| Version | ClawHub |
| --- | --- |
| 1.2.0 | [rails-ci-fixer v1.2.0](https://clawhub.ai/djc00p/skills/rails-ci-fixer) |

---

**Published by [@djc00p](https://github.com/djc00p)**
