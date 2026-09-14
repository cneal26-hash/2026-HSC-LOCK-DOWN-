# HSC Lock-In 2026

A focused, serious study command centre for Chris's 2026 HSC run-in.

## Included

- Today dashboard with the one-of-each stack: English, Business, Economics, Maths and Drama.
- Instant click interactions with no page reload.
- Total Completion checklist across every subject.
- English memorisation chains with six-step progression.
- Corrected Economics list: 23 essays across four topics.
- Two-phase plan:
  - Phase 1: priority work due Friday 25 September — English Module B, Economics Topic 1, Business Human Resources, plus an optional 25% Maths target.
  - Phase 2: reassess at the checkpoint, then run full no-interruption memorisation, spaced repetition, perfection and practice.
- Official countdowns for English Advanced, Mathematics Standard 2, Drama, Business Studies and Economics.
- Study-hour schedule using the supplied 3 / 4.5 / 0 / 5 / 10 / 10 / 0 / 8 / 8 / 8 / 10 hour run-up.
- Local persistence and a canonical data/state.json file for chat-driven progress updates.

## GitHub Pages

The included workflow deploys the root of the repository to GitHub Pages after pushes to main.

After the first push, open repository Settings, then Pages, and set the source to GitHub Actions if GitHub has not enabled it automatically.

Expected URL: https://cneal26-hash.github.io/2026-HSC-LOCK-DOWN-/

## Updating the live state from chat

The frontend polls data/state.json every 60 seconds. When a progress update is sent in chat, update that file and increment revision. The page will merge the new canonical state without needing a code rebuild.

The site also accepts natural-language updates in its Quick Log box, but those are saved locally in the browser. GitHub state remains the canonical cross-device source.
