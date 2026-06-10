# Zero to Hero · Idea to App — Repo

Source-of-truth repository for the **text artifacts** of *Zero to Hero · Idea to App*, a feature documentary following a 6-month applied-AI cohort (30 students). Working title. Team of 5.

> Read this page first. It tells you what this repo is, what it isn't, and where the rest of the work actually lives.

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
| `.github/ISSUE_TEMPLATE/` | Scene idea / Interview lead / Followup forms |

## What this repo IS NOT

- **Not a footage store.** No `.mp4`, `.mov`, `.wav`, `.psd`, `.prproj`, `.aep`. The `.gitignore` blocks them. → **Drive / LucidLink**.
- **Not a footage-review tool.** No timecoded comments here. → **Frame.io**.
- **Not a chat app.** Discussion happens in issues and PR comments, not commit messages. → **WhatsApp** for urgent only.
- **Not a real-time editor.** No live cursors. If two people need to write together right now, do it elsewhere and PR the result back here.
- **Not a backup.** Don't put one-of-a-kind originals here. Anything irreplaceable belongs in Drive/LucidLink with a backup policy.

---

## Where the work actually lives

| Tool | Use for | Don't use for |
|---|---|---|
| **GitHub** (this repo) | Text artifacts. Decisions of record. Async status. Structured issues. | Footage, raw audio, real-time chat. |
| **Google Drive / LucidLink** | Raw footage, audio masters, signed releases, contracts, shareable PDFs. | Anything that benefits from diff + history. |
| **Frame.io** | Cut review. Timecoded notes. Editor ↔ director feedback. | Long-form written discussion. |
| **WhatsApp** | Urgent decisions only. ≤ 5 messages per thread. | Anything you'd want findable in 3 months. |
| **Zoom** | Bi-weekly 30-min team check-in (Munish chairs). Bilateral if a WhatsApp thread exceeds 5 messages. | Routine status — that goes in the Friday README update. |

**Rule of thumb:** if you want it findable, decided, or attributable later, it lives in this repo. If it's heavy bytes, it lives in Drive/LucidLink or Frame.io. If it's right-now-or-never, WhatsApp.

---

## Cadence

Pulled from the v3 deck (`playbook/zero-to-hero-deck-2025-06-10.pptx`), Slide 5.

- **Every Friday** — each workstream owner posts a 3-line update to the repo:
  - **STATUS:** On track / At risk / Blocked
  - **THIS WEEK:** one sentence on what happened
  - **NEXT WEEK:** one sentence on what's coming
- **Bi-weekly, 30 min** — full-team Zoom. Munish chairs. Hard commitment — no skipping.
- **As needed** — bilateral Zoom when a thread is going nowhere on WhatsApp.

---

## Git workflow

- Branch for every change: `docs/<topic>`. Never commit straight to `main`.
- One PR per logical change.
- Conventional commit subjects, lowercase imperative: `add` / `update` / `fix` / `refactor`.
- Body explains the **why**, not the **what** — the diff already shows the what.
- No force-push to `main`. No `--no-verify`.

## Issues

File from the *New issue* page. Three templates:

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
