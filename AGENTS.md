# edit-anantf

Instructions for every AI assistant working here (Claude Code reads this through `CLAUDE.md`).
Shortcut that serves edit.anantf.com: `index.html` and `404.html` redirect `edit.anantf.com/<page>` to the page
editor on anantf.com (see `README.md`). Four files, published by GitHub Pages (`CNAME`); the editor itself lives in
NTF-Anaesthesia/anantf-site.

Anything merged here is public. Keep only code and docs: no secrets, tokens, personal data or patient details.

## Rules that bite

- `index.html` and `404.html` carry the same redirect and the same `MOVED` list; change both together.
- When a page moves to its own repo, add it to `MOVED` in both files.

## Private notes and repo layout

Private notes: `NTF-Anaesthesia/ntf-hub-attach-always` (private, org members only). At the start of a session attach it
(`add_repo`) and read its `AGENTS.md`; save lasting notes there, never here. Repo layout: one repo per app or app
group, public code plus a `-private` pair; this repo has no pair (no notes or data); notes go in the hub. A new app
gets its own repo (test in ntf-hub-attach-always `hub/new-repo.md`), never a folder here.
