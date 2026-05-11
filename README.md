# Jengo Docs

Setup guides for forking and joining Jengo.

## Who this is for

Anyone who wants to run their own Jengo agent — either as part of the ProsperGenics team or as an independent fork of the Jengo architecture.

## Documents

| Document | Description |
|---|---|
| [fork-instructions.html](fork-instructions.html) | Complete step-by-step guide: fork the public repos, create your private and machine repos, clone everything locally, add upstream remotes, and make your first customizations. |

## Quick start

Open `fork-instructions.html` in your browser and follow the steps.

For ProsperGenics team members: your public repos to fork are in the `scp-jengo` GitHub organization (`jengo-*-prospergenics`). For a standalone Jengo fork, fork from `martiendejong/jengo-*-public`.

## Repo structure

Jengo uses three tiers per module (identity / system / knowledge / world):

- **public** — the architecture layer, fork this to get started
- **private** — your agent's personal state, create fresh
- **machine** — local secrets and paths, create fresh, never share

All 12 repos live in one local folder. The setup guide walks through each step.
