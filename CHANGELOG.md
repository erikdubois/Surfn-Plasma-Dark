# Changelog

## 2026.06.23 — README install commands

### What Changed

**Install docs:** the README install section now lists the meta packages (top-level `*-icons-meta`, plus the group meta where applicable) alongside the per-variant `*-icons-git` package — replacing the outdated single `pacman -S` line.

### Files Modified

- README.md

## 2026.06.21 — repo standardisation

### What Changed

Added the standard project docs and corrected the README, which falsely claimed the
repo shipped four themes and inherited the base Surfn icon set.

### Technical Details

- README rewritten to reflect reality: ships only `Surfn-Plasma-Dark`, which
  `Inherits=breeze-dark,breeze,hicolor` — not the base Surfn set. The package
  `surfn-plasma-dark-icons-git` has no hard dependencies (`depends=()`).
- Added CLAUDE.md.

### Files Modified

- README.md, CHANGELOG.md, CLAUDE.md
