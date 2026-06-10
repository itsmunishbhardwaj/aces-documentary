# Aces Documentary

Version control for the **text artifacts** of a feature documentary following a 6-month applied AI cohort (~34 students). Team of 5.

> **Video, audio, and editorial project files do NOT live here.** See `.gitignore`.


---

## What this repo IS

Text. Version-controlled. PR-reviewed. Five-person team. No binary assets.

| Folder | Contents |
|---|---|
| `playbook/` | Production playbook — v2 long form + v3 simplified deck |
| `scripts/` | Treatments, outlines, voiceover drafts, scene scripts |
| `interviews/transcripts/` | Interview transcripts (text only) |
| `production/` | Call sheets, shot lists, releases, schedules, contact sheets |
| `story/` | Story bible, character arcs, threads, beat sheets |
| `distribution/` | Festival strategy, press, release planning |
| `meta/` | How we work — roles, conventions, decisions |

## What this repo IS NOT

- **Not a footage store.** No `.mp4`, `.mov`, `.wav`, `.psd`, `.prproj`, `.aep`. The `.gitignore` blocks them. → **Drive / LucidLink**.
- **Not a footage-review tool.** No timecoded comments here. → **Frame.io**.
- **Not a chat app.** Discussion happens in issues and PR comments, not commit messages. → **WhatsApp** for daily comm.
- **Not a live multi-user editor**: Use google docs on docs multiple people want to work actively on. Commit the final **draft** here.

---

## Where the work actually lives

| Tool | Use for | Don't use for |
|---|---|---|
| **GitHub** (this repo) | Text artifacts. Decisions of record. Async status. Structured issues. | Footage, raw audio, real-time chat. |
| **Google Drive / LucidLink** (TBD) | Raw footage, audio masters, signed releases, contracts, shareable PDFs. | Anything that benefits from diff + history. |
| TBD | Cut review. Timecoded notes. Editor ↔ director feedback. | Long-form written discussion. |
| **WhatsApp** | Primary Mode of Communication |
| **Zoom** | Meetings, etc. |

---

## Git workflow

- Branch for every change: `docs/<topic>`. Never commit straight to `main`.
- One PR per logical change.
- Conventional commit subjects, lowercase imperative: `add` / `update` / `fix` / `refactor`.
- Body explains the **why**, not the **what** — the diff already shows the what.
- No force-push to `main`. No `--no-verify`.

## Issues

File from the *New issue* page. Three templates (so far, we can add more):

- **Scene idea** — pitch a scene, sequence, or moment for the film.
- **Interview lead** — propose a subject to interview.
- **Followup** — production / story / post / distribution action items.

Blank issues are disabled by design — pick a template.

---

## Roles

See `meta/roles.md`. The v3.0 roles matrix is on Slide 4 of the deck.

## Status of the platform itself

- Repo: **private** on GitHub.
- Branch protection: deferred (free-tier private repos don't get it). Convention is enforced socially via the workflow above.
- Owners with push access: the 5-person team.

*Last edited: 2025-06-10.*
