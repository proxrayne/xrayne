---
name: proxrayne-release-project
description: Release and public installation repository guidance for Proxrayne xrayne. Use when Codex works on the public README, install/uninstall scripts, release artifact names, CLI installation instructions, API/UI image archive documentation, or public distribution behavior in the xrayne repository.
---

# Proxrayne Release Project

## Quick Start

Read `references/release-map.md` before changing release documentation or scripts. Use `$proxrayne-project` first when the task affects `xrayne-panel`, `xrayne-ui`, or `xrayne-cli` release production, public asset names, or installer/runtime contracts across repositories.

## Rules

- Keep this repository focused on public release/install documentation and scripts.
- Do not add panel, node, CLI source, dashboard source, or build-system code here.
- Keep release asset names aligned with the CLI, panel, and UI release workflows and public README.
- Keep install/uninstall scripts safe, explicit, and consistent across PowerShell and shell variants.
- Document user-facing behavior in `README.md` when script behavior or release artifact expectations change.
