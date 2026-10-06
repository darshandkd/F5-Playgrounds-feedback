# How to file a useful issue

Thank you for taking the time to report something. A clear, specific issue is far more useful than a vague one — here's what makes the biggest difference.

## For bug reports

A good bug report gives the maintainer everything needed to reproduce the problem in 30 seconds:

1. **Which playground** — Gallery, AI Playground, BIG-IP, NGINX, XC Distributed Cloud, F5 Insight, EOB, or "another / not listed". This is the most important field — it routes your issue to the right place.
2. **Where exactly** — paste the scenario link from your address bar (every scenario has its own URL), plus the button you clicked
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

Issues are read and labelled by type (`bug`, `enhancement`, `question`) by playground (`gallery`, `ai-playground`, `bigip`, `nginx`, `xc`, `insight`, `eob-playground`, `cross-cutting`, or `playground:future` for a playground that doesn't exist yet) and by priority. Good ideas that aren't scheduled yet get the `roadmap` label and stay open.

There is **no committed response time, and no commitment to implement any report or request.** Filing an issue is not a work order — it's input. Some issues are picked up, some are kept for later, and some are closed without action. If more detail is needed, someone may ask; if an issue goes quiet it may be closed. When something changes on the live site as a result, the issue gets a short release note with a direct link and is closed with the `fixed` label.

## What this repo is *not*

- Not a place to request the source code (it's intentionally private)
- Not a support channel for F5 products (use [my.f5.com](https://my.f5.com) for that)
- Not a discussion board

## A note on language

Please write in plain English. If English isn't your first language, that's fine — write what you can.
