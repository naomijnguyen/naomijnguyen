# Jennifer Naomi Nguyen

Immunology researcher building software. Ten-plus years in pharmaceutical and academic research, including Vaccines and Oncology R&D at Pfizer, and three programs that reached clinical trials. Since June 2025 I've been building systems for working with language models, and treating them the way I'd treat any instrument: measure it, find out what the measurement is actually picking up, then trust the result.

**[naomijnguyen.com](https://www.naomijnguyen.com)** — interactive portfolio: projects, architecture notes, and the decisions behind them.

### What I build

- **Multi-provider LLM orchestrator** — models from different providers working through a shared workflow, with an evaluation harness for comparing prompts. A pilot ran 359 usable generations across three models; analysis turned up a classification rule that was missing cases, which meant fixing it and recomputing.
- **Context and memory workspace** — chat, a generated wiki, search, and background memory updates on Cloudflare Workers: Durable Objects, KV, D1, nine bindings on one Worker.
- **Agent coordination** — five coding agents against one repository, with bounded assignments, backward tracing from symptom to cause, and independent verification of each fix.
- **96-well plate analyzer** — plate maps and reader output into results I can interpret, built from the version of that task I used to do by hand.

### Tech stack and AI collaboration

I build with JavaScript, TypeScript, Python, React, Node.js, npm, HTML, CSS, Markdown, Hugo, Cloudflare Workers, Git, GitHub, and Visual Studio Code.

Since June 2025, I’ve been making software in active collaboration with AI coding systems across providers: Claude and Claude Code from Anthropic, Codex from OpenAI, GitHub Copilot from GitHub and Microsoft, Gemini from Google, and Grok from xAI. These projects are what I made through that collaboration, and I want to do more of it.

### Elsewhere

[Portfolio](https://www.naomijnguyen.com) · [ORCID](https://orcid.org/0000-0001-8295-6767) · [naomi@naomijnguyen.com](mailto:naomi@naomijnguyen.com)

---

*This repository also holds a small Hugo site for research notes — longer and rougher than the portfolio, published while the thinking is still in progress.*
