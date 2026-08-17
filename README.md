# F5 Playgrounds — Feedback & Issue Tracker

This repository is the **public issue tracker** for the **[F5 Playgrounds collection](https://playgrounds.darshandkd.com/)** — a growing set of hands-on, interactive demonstrations of F5's product portfolio, with a single Gallery as the entry point.

> **Heads-up:** This repo intentionally contains **no source code**. The applications themselves live in a separate private repository.
> Everything here is for filing bugs, requesting features, and asking questions about the live experiences.
>
> Feedback is welcome and read, but there is **no committed response time and no commitment to implement any report or request.** Filing an issue is input, not a work order.

---

## What's in the F5 Playgrounds collection

| Playground | What it demonstrates |
|---|---|
| **[Gallery](https://playgrounds.darshandkd.com/)** | The umbrella landing page — discover and launch any playground |
| **[AI Playground](https://playgrounds.darshandkd.com/ai-playground/)** | 36 interactive simulations across **Inference** (9), **Safety & Security** (7 — including **AI Workflow Governance** powered by **SurePath AI**, and **F5 AI Gateway** across its Model and MCP planes), and **Data Delivery** (5), plus **12** animated AI-concept explainers, an **AI Security** section (adversarial techniques + AI guardrails), and a catalog of F5's **AI product portfolio** (BIG-IP Next for Kubernetes, AI Guardrails, AI Red Team, SSL Orchestrator, and more) |
| **[BIG-IP Playground](https://playgrounds.darshandkd.com/bigip/)** | F5 BIG-IP simulator — **fully live across all five core modules with 30 deeply-animated use-cases**: **LTM** (6 — load balancing, DAG disaggregation, SSL offload, persistence, health monitoring, iRules) · **WAF/ASM** (6 — signature blocking, brute force, bot defense, behavioral L7 DoS, IP intelligence, and **AI Risk Scoring**: a 1–100 risk score that decides whether a signature match is actually an attack, so the same match can be delivered or stopped) · **AFM** (3 — network firewall policy, L3/4 IP intelligence, device DoS) · **Zero Trust Access** (8 — *formerly APM*: Visual Policy Editor SSO, SAML IdP, per-request authorization, endpoint posture, OAuth→KCD, Entra ID OIDC, HTTP Connector→OPA, CAC/smart-card) · **DNS** (7 — GSLB resolution, topology LB, DNS Express, DNSSEC signing, GSLB failover, agentic-AI steering) |
| **[EOB Playground](https://playgrounds.darshandkd.com/eob-playground/)** | **F5 eBPF Observability for 5G — built with MantisNet.** Kernel-level visibility across the 5G fabric (RAN → 5G Core → Data Network) through three labs: the **Linux Kernel**, the **eBPF lifecycle** (write → verify → load → observe safely), and a **live 5G fabric** streaming kernel-level telemetry from every network function |
| **[XC Distributed Cloud](https://playgrounds.darshandkd.com/xc/)** | **F5 Distributed Cloud — 19 scenarios across five modules.** **Multi-Cloud Networking** (5 — Network Connect L3, App Connect L7 "connect apps, not networks", Segmentation, Service Mesh, Customer Edge Deploy-Anywhere) · **WAAP** (5 — WAF attack signatures, API discovery & schema validation, L7 DDoS, web-app scanning, **AI Risk Scoring**) · **Bot Defense & Fraud** (6 — adaptive bot defense, per-request signal detection, client-side / Magecart defense, account protection, authentication intelligence, agentic-AI commerce) · **App Delivery & Edge** (3 — DNS & GSLB, CDN, App Stack / vK8s) — plus platform **Fundamentals** (Regional Edges, Customer Edges, the F5 Global Network). |
| **[NGINX Playground](https://playgrounds.darshandkd.com/nginx/)** | **Now live — 17 scenarios across six modules:** **NGINX Fundamentals** (5) · **NGINX Plus** (5 — dynamic upstreams, cluster state sync, content caching, active health checks, and more) · **F5 WAF + DoS for NGINX** (2) · **NGINX for Kubernetes** (2 — Gateway Fabric) · **NGINX One** (2 — fleet CVE & drift radar, config sync groups) · **NGINXaaS** (1) |
| **More on the way** | Future playgrounds will appear here as they ship |

This tracker captures feedback for **all** of them — current and future. Use the **"Which playground?"** dropdown when filing an issue so it routes correctly.

---

## How to use this repo

### Found a bug?
[Open a Bug Report](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/new?template=bug_report.yml). Please include:
- Which playground (Gallery, AI Playground, BIG-IP Playground, XC Distributed Cloud, NGINX Playground, EOB Playground, or another)
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
- Filter by playground: [`gallery`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Agallery) · [`ai-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aai-playground) · [`bigip-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Abigip-playground) · [`xc-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Axc-playground) · [`nginx-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Anginx-playground) · [`eob-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aeob-playground)

---

## Code of conduct

Be kind. Assume good intent. Reports that include slurs, harassment, or off-topic content will be closed without comment.
