# CLAUDE.md — neo-candy-luv

## Project overview

Standalone repo for the **neo-candy-luv** folder-icon theme — the same folder set as
`erikdubois/surfn-luv` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-luv/` — folders only. Packaged as `neo-candy-luv-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-luv/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
