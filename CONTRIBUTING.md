# How to file a useful issue

Thank you for taking the time to report something — well-written issues get fixed faster than vague ones. Here's what makes the biggest difference.

## For bug reports

A good bug report gives the maintainer everything needed to reproduce the problem in 30 seconds:

1. **Which playground** — Gallery (the umbrella landing), AI Playground, EOB Playground, or "another / not listed". This is the most important field — it routes your issue to the right place.
2. **Where exactly** — tab name, sidebar item, button you clicked
3. **What you expected** vs **what happened**
4. **Reproduction steps** — numbered, in order
5. **Browser + OS + viewport size** — Chrome 138 / macOS 14 / 1440×900 desktop
6. **Screenshot or screen recording** — even a quick crop helps a lot
7. **Console errors** — open DevTools (F12 / Cmd+Opt+I), check the Console tab, paste any red errors

## For feature requests

1. **The use case** — who would benefit and what they're trying to accomplish
2. **The current gap** — what about the playground falls short today
3. **Rough sketch** — a one-paragraph description, optional mockup or reference link

## For questions

Search [open and closed issues](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=is%3Aissue) first — common questions are often already answered. If you don't find an answer, file a Question issue.

## What happens after you file

- **Triage** (1-3 business days): we add labels for type (`bug`, `enhancement`, `question`) and playground (`gallery`, `ai-playground`, `eob-playground`, or `playground:future` for ideas about a playground that doesn't exist yet) plus a priority
- **Investigation**: we may ask for more details — please respond, otherwise we'll close the issue after 14 days of silence
- **Fix**: code changes happen in the private source repo. When the fix ships to the live site, we close your issue with a comment and the `fixed` label

## What this repo is *not*

- Not a place to request the source code (it's intentionally private)
- Not a support channel for F5 products (use [my.f5.com](https://my.f5.com) for that)
- Not a discussion board (we may add Discussions later if there's demand)

## A note on language

Please write in plain English. If English isn't your first language, that's fine — write what you can and we'll work with it.
