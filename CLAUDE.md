# CLAUDE.md — surfn-plasma-dark

## Project overview

Standalone repo for the **Surfn Plasma Dark** icon theme, split out of the
`erikdubois/surfn` monolith. See [README.md](./README.md).

## Current state

Ships one theme: `usr/share/icons/Surfn-Plasma-Dark/`. Packaged as
`surfn-plasma-dark-icons-git` (recipe in `~/KIRO-PKG-BUILD-ICONS/surfn-plasma-dark/`),
no package dependencies. Several sibling themes (qogir, tela, light, flow) `Inherits` this one.

## Patterns & decisions

- Theme dir PascalCase; repo/package lowercase. `icon-theme.cache` rebuilt by the pacman
  hook on install. Theme `Inherits=breeze-dark,breeze,hicolor` — it does **not** inherit
  base Surfn. Bash scripts follow the canonical Kiro template.
