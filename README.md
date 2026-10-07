# OpenPrototyping

A Replit workspace export containing only the project's icon and Replit workspace-state data — no project source code.

## Features

None implemented in this repo.

## Tech stack

Not determinable — no source code is present.

## Project structure

```
├── generated-icon.png      # project icon
├── project-source.zip      # contains only .local/ (Replit agent state, workflow logs,
│                           # agent skills) and .agents/skills/ — no application source
└── .agents/agent_assets_metadata.toml
```

## Status

**Stub.** The zip archive's 893 entries are all Replit internal state (agent memory, workflow logs, built-in agent skills); there is no application code, no package manifest, and no docs. The repo appears to be an automated export of the Replit workspace at https://replit.com/@jclarkagain/OpenPrototyping. Anything the project does lives on Replit, not here.
