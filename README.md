# Startup founder outreach

A step-by-step playbook, also usable as an AI-agent skill, for cold-emailing early-stage startup founders. It is an unofficial summary condensed from Backdoor's public posts and guides, with credit and source links throughout.

- [@textbackdoor](https://x.com/textbackdoor) on X
- [backdoorai.app](https://backdoorai.app)

This repository is not affiliated with Backdoor. Templates and other quoted material belong to their authors and are included with attribution. The MIT license covers the original summary and code in this repository only.

## The method

1. Pick 8 to 20 early-stage startups (pre-seed to Series C) that just raised money, launched, or started hiring — preferably in a field you already know.
2. Email the founder directly, not HR, using an address you found published.
3. Spend 45 minutes to 2 hours making one small, real thing for them first.
4. Keep the email under about 120 words: open with their news, give one proof with a number, say why this startup, and make one yes-or-no ask (a 15-minute call or a referral).
5. Follow up once around day 4 in the same thread, and add something new instead of "just checking in."
6. On a yes, bring a 30-day plan to the call. On a no, thank them and ask for one other intro.

## Repo layout

- `SKILL.md` — short agent skill you can drop into a skills folder
- `notes.md` — full research notes, with templates quoted word for word and source links
- `data/posts.json` — raw public posts collected from @textbackdoor
- `LICENSE` — MIT license for the original summary and code in this repo only

## Using the skill

Copy `SKILL.md` into a skills folder for Cursor or another agent (for example `.cursor/skills/startup-founder-outreach/SKILL.md`). The agent can then follow the playbook to pick targets, find founder emails, suggest proof work, and draft emails for you to review and send. The skill drafts only; it does not send mail or invent proof, metrics, or email addresses.

For the full templates and source citations, see `notes.md`.
