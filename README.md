# F5 Playgrounds — Feedback & Issue Tracker

This repository is the **public issue tracker** for the **[F5 Playgrounds collection](https://playgrounds.darshandkd.com/)** — a growing set of hands-on, interactive demonstrations of F5's product portfolio, with a single Gallery as the entry point.

> **Heads-up:** This repo intentionally contains **no source code**. The applications themselves live in a separate private repository.
> Everything here is for filing bugs, requesting features, and asking questions about the live experiences.

---

## What's in the F5 Playgrounds collection

| Playground | What it demonstrates |
|---|---|
| **[Gallery](https://playgrounds.darshandkd.com/)** | The umbrella landing page — discover and launch any playground |
| **[AI Playground](https://playgrounds.darshandkd.com/ai-playground/)** | 30+ interactive simulations across Inference, Safety, and Data Delivery, plus 14 animated AI concept explainers |
| **[EOB Playground](https://playgrounds.darshandkd.com/eob-playground/)** | F5 eBPF Observability for 5G — kernel-level visibility on every Kubernetes node, sidecar vs eBPF comparison, TLS blind-spot inspection, capacity-at-scale ROI, and a deep eBPF lifecycle lab |
| **More on the way** | Future playgrounds will appear here as they ship |

This tracker captures feedback for **all** of them — current and future. Use the **"Which playground?"** dropdown when filing an issue so it routes correctly.

---

## How to use this repo

### Found a bug?
[Open a Bug Report](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/new?template=bug_report.yml). Please include:
- Which playground (Gallery, AI Playground, EOB Playground, or another)
- Which simulation, tab, or feature
- Browser + OS
- A screenshot if visual
- Steps to reproduce

### Have a feature idea?
[Suggest a Feature](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/new?template=feature_request.yml). Tell us what you want to demonstrate or learn that the playgrounds don't cover yet — including ideas for **entirely new playgrounds**.

> Pitching a brand-new playground? The visual language, layout, theme, and component patterns that every playground follows are documented in `DESIGN.md` (in the source repo). It's the single source of truth for keeping new additions native to the family.

### Just have a question?
[Ask a Question](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/new?template=question.yml) or check existing issues — yours might already be answered.

### Browsing existing reports
- [All open issues](https://github.com/darshandkd/F5-Playgrounds-feedback/issues)
- [Bugs](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Abug+is%3Aopen)
- [Feature requests](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aenhancement+is%3Aopen)
- [Recently fixed](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Afixed+is%3Aclosed)
- Filter by playground: [`gallery`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Agallery) · [`ai-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aai-playground) · [`eob-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aeob-playground)

---

## Triage & response

Maintained by **[@darshandkd](https://github.com/darshandkd)** (d.doshi@f5.com).

Typical response window: **2-3 business days**. Reproducible bugs with screenshots usually get triaged the fastest. Feature requests are evaluated quarterly against the demo roadmap.

When a fix ships, you'll see it on the live URL within ~5 minutes of the maintainer closing the issue.

---

## Why is this repo separate from the source code?

The playgrounds are built and maintained by an internal F5 marketing/engineering function. The source is kept private to protect ongoing product roadmap work, but the experiences themselves are publicly accessible — and we want a public way to hear from the people using them.

---

## Code of conduct

Be kind. Assume good intent. Reports that include slurs, harassment, or off-topic content will be closed without comment.
