# CLAUDE.md - DarkRef Releases

This repo is DarkRef's public download page: the README, plus the GitHub
releases that carry the Windows installers. The app's source, and the main
CLAUDE.md with the full working rules, are in `TimDommett/DarkRefElectron`.

## This repo is public

Anyone can read it. Never commit secrets, internal links, user data or
unreleased plans, and keep internal detail out of replies to GitHub issues too.

## Releases come from DarkRefElectron

The Release (Windows) workflow in DarkRefElectron publishes each release here,
with notes from its `RELEASE_NOTES.md`. The Windows app updates itself from
these releases, so don't create, edit or delete a release or tag by hand unless
Tim asks.

## Tasks live in Tickets (project DR)

Work on this repo is tracked with all other DarkRef work, in Tim's private
tracker Tickets, project **DR** (use the Tickets MCP). The flow is simple:

- Every request becomes a DR ticket assigned to `claude`, quoting Tim's words.
  There is no planning step: start straight from the ticket.
- Move it to In Progress, link the PR, do the work, add evidence in a short
  comment and move it to In Review. Tim reviews, merges and moves it on; never
  move a ticket past In Review yourself.
- A bug report or feature request opened as a GitHub issue here gets a DR
  ticket that links to it.
- Anything only Tim can do becomes a DR ticket assigned to him, with numbered
  steps.
