# Contributing to Tilawaty App (Issues Tracker)

Thank you for helping improve Tilawaty. This repository is an **issues-only** public tracker. The app source code is private, so we do **not** accept code pull requests for the app itself.

## What you can contribute

- Bug reports
- Feature requests
- Translation / Quran content corrections
- Documentation improvements for **this** repository (README, templates, guides)
- Discussion in [Discussions](https://github.com/muhamm-ad/TilawatyApp/discussions)

## What we do not accept here

- App source code patches or feature PRs against the app.
- Personal data, private notes from backups, or account credentials (Tilawaty has no accounts; still never paste private notes)
- Security vulnerabilities as public issues, use [private reporting](SECURITY.md)

## Filing a good issue

1. **Search first**: check existing [issues](https://github.com/muhamm-ad/TilawatyApp/issues) and [discussions](https://github.com/muhamm-ad/TilawatyApp/discussions) to avoid duplicates.
2. **Use a template**: blank issues are disabled; pick the matching form.
3. **One concern per issue**: separate bugs and features into their own issues.
4. **Title style**: use Conventional Commits style in English, with a short area scope when possible:
   - `fix(reading): verses cut off after font size change`
   - `feat(audio): option to change reciter mid-surah`
   - `fix(translations): typo in Hamidullah for Surah X ayah Y`
5. **Be specific**: for bugs, include version, platform/OS, steps, expected vs actual. Screenshots help.

## Labels

Maintainers apply labels. New issues start with `needs-triage` plus a type (`bug` / `enhancement` / etc.). After triage you will typically see:

- A **priority**: `priority: high` | `priority: medium` | `priority: low`
- An **area**: e.g. `area: reading`, `area: progress`, `area: bookmarks`, `area: audio`, `area: translations`, `area: reminders`, `area: backup`, `area: settings`, `area: browse`, `area: i18n`, `area: ui`, `area: a11y`, `area: performance`
- Possibly `needs-info`, `confirmed`, `tracked-in-app`, or `website-impact`

## Pull requests (this repo only)

PRs that improve docs or issue templates in **this** repository are welcome. Keep them focused and in English. See `.github/pull_request_template.md`.
