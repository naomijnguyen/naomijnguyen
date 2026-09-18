# Jennifer Nguyen

Immunology researcher building software. Ten-plus years in pharmaceutical and academic research, including Vaccines and Oncology R&D at Pfizer, and three programs that reached clinical trials. Since 2024 I've been building systems for working with language models, and treating them the way I'd treat any instrument: measure it, find out what the measurement is actually picking up, then trust the result.

**[naomijnguyen.com](https://www.naomijnguyen.com)** — interactive portfolio: projects, architecture notes, and the decisions behind them.

### What I build

- **Multi-provider LLM orchestrator** — models from different providers working through a shared workflow, with an evaluation harness for comparing prompts. A pilot ran 359 usable generations across three models; analysis turned up a classification rule that was missing cases, which meant fixing it and recomputing.
- **Context and memory workspace** — chat, a generated wiki, search, and background memory updates on Cloudflare Workers: Durable Objects, KV, D1, nine bindings on one Worker.
- **Agent coordination** — five coding agents against one repository, with bounded assignments, backward tracing from symptom to cause, and independent verification of each fix.
- **96-well plate analyzer** — plate maps and reader output into results I can interpret, built from the version of that task I used to do by hand.

### Elsewhere

[Portfolio](https://www.naomijnguyen.com) · [ORCID](https://orcid.org/0000-0001-8295-6767) · [naomi@naomijnguyen.com](mailto:naomi@naomijnguyen.com)

---

*This repository also holds a small Hugo site for research notes — longer and rougher than the portfolio, published while the thinking is still in progress.*
