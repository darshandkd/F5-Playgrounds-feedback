# F5 Playgrounds — Feedback & Issue Tracker

This is the **public issue tracker** for **[F5 Playgrounds](https://playgrounds.amer-ent.f5demos.com/)**: hands-on, animated simulations of F5's portfolio that you can run in a browser. No install and no account; press **Run** and watch what the product does.

> This repo has **no source code**. The playgrounds live in a separate private repository.
> Use it to report bugs, request features and ask questions about the live site.
> Feedback is read, but there is **no committed response time and no commitment to implement** any request. An issue is input, not a work order.

---

## The playgrounds

Most scenarios follow the same pattern: a short premise, an animated diagram, one **Run** button, and an **on/off switch** for the F5 product so you can compare *with* and *without* it. Every scenario also links to the official F5 documentation through its docs chip; where F5 hasn't published a page yet, the chip says **Soon**.

**Recently shipped from your feedback:** [#1 Prefill–Decode Disaggregation](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/1) · [#2 Secure Agentic Delivery](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/2) · [#3 Direct links to any playground, module or scenario](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/3).

| Playground | What you can explore |
|---|---|
| **[Gallery](https://playgrounds.amer-ent.f5demos.com/)** | The landing page. Pick any playground from here. |
| **[AI Playground](https://playgrounds.amer-ent.f5demos.com/ai-playground/)** | How F5 delivers and secures AI. **Inference** (8, F5 BNK, NGINX Gateway Fabric and BIG-IP): Prompt Routing, Semantic Caching, Inference-aware Load Balancing, **Prefill–Decode Disaggregation** (new, BNK 2.4), EPP Inference Router, Token Governance, RAG Pipeline, **Secure Agentic Delivery** (new, BNK 2.4). **Safety & Security** (5): F5 AI Guardrails, F5 AI Red Team, F5 Workforce AI, F5 AI Powered WAF, F5 AI Gateway (in development). **Data Delivery** (5). **AI Concepts** (11 explainers, from how LLMs think to MCP). **AI Threats** (7 real incidents). **F5 Products** (the AI portfolio). |
| **[BIG-IP](https://playgrounds.amer-ent.f5demos.com/bigip/)** | 32 scenarios across five modules. **LTM** (8): load balancing, full proxy, DAG, SSL offload, SNAT, persistence, health monitoring, iRules. **WAF** (6): signatures, brute force, bot defense, behavioral L7 DoS, IP intelligence, AI Powered WAF. **AFM** (3). **APM / Zero Trust Access** (8). **DNS** (7). Plus a BIG-IP **MCP server** tool. |
| **[NGINX](https://playgrounds.amer-ent.f5demos.com/nginx/)** | **NGINX Plus** (dynamic upstreams, cluster state sync, content caching, active health checks, WAF policy, L7 DoS), **NGINX for Kubernetes** (Gateway Fabric), **NGINX One** (fleet CVE and drift, config sync), **NGINXaaS**. Plus a fundamentals glossary and an MCP server tool. |
| **[F5 Distributed Cloud (XC)](https://playgrounds.amer-ent.f5demos.com/xc/)** | 19 scenarios. **Multi-Cloud Networking** (5), **WAAP** (5), **Bot Defense & Fraud** (6), **App Delivery & Edge** (3). Plus platform fundamentals and an XC MCP server tool. |
| **[F5 Insight](https://playgrounds.amer-ent.f5demos.com/insight/)** | **New.** BIG-IP fleet observability and an AI assistant: 16 scenarios across Connect, Fleet, Detect, Ask Insight, Manage and Govern. |
| **[EOB](https://playgrounds.amer-ent.f5demos.com/eob-playground/)** | F5 eBPF Observability for 5G, built with MantisNet. Kernel-level visibility from RAN to 5G Core, through EOB and eBPF labs and a live 5G fabric. |

### Sharing a scenario

Every playground, module and scenario has its own link, for example
`https://playgrounds.amer-ent.f5demos.com/bigip/ltm/full-proxy`.
Copy the address bar to send someone straight to it. Please include that link in any issue too.

---

## Filing an issue

| You want to… | Use |
|---|---|
| Report something broken or wrong | [Bug report](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/new?template=bug_report.yml) |
| Suggest a scenario, feature or new playground | [Feature request](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/new?template=feature_request.yml) |
| Ask how something works | [Question](https://github.com/darshandkd/F5-Playgrounds-feedback/issues/new?template=question.yml) |

A good report includes:
- the scenario link;
- what you expected vs what you saw;
- your browser and OS;
- a screenshot.

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

For questions about F5 products themselves, use [F5 Support](https://my.f5.com), not this tracker.

---

## What happens next

1. **Acknowledged.** A bot replies within moments, so you know it landed.
2. **Triaged.** The issue is labelled by type, playground and priority, with a short note on how it's understood.
3. **Planned or roadmapped.**
   - Work that will happen soon gets a plan.
   - Good ideas that aren't scheduled yet get the `roadmap` label and **stay open**.
4. **Shipped.** When a change goes live, the issue gets a short release note with a direct link to it on the site, and is closed with the `fixed` label.

Some issues are closed without action, with a reason. If more detail is needed, you'll be asked in the issue.

### Browse

- [All open issues](https://github.com/darshandkd/F5-Playgrounds-feedback/issues)
- [Roadmap](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aroadmap)
- [Bugs](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Abug+is%3Aopen)
- [Feature requests](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aenhancement+is%3Aopen)
- [Recently shipped](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Afixed+is%3Aclosed)
- By playground: [`gallery`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Agallery) · [`ai-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aai-playground) · [`bigip`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Abigip) · [`nginx`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Anginx) · [`xc`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Axc) · [`insight`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Ainsight) · [`eob-playground`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Aeob-playground) · [`cross-cutting`](https://github.com/darshandkd/F5-Playgrounds-feedback/issues?q=label%3Across-cutting)

---

## A note on accuracy

The scenarios are **conceptual demos**. Product behaviour and terms follow F5's public documentation, but timings, counts and metrics are simulated for the demo, not measured product performance. If you spot a claim that doesn't match F5's docs, that's a bug we want to hear about.

## Code of conduct

Be kind and assume good intent. Reports with harassment, slurs or off-topic content are closed without comment.
