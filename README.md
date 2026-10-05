# Hi, I’m Evan Liu

I’m a Data Science major at UC Davis, interested in building data driven apps using ML and AI. Below are some of my favorite recent projects.

---

## Projects

### [AI Checkout](https://github.com/evanxliu1/AICheckout)

A Chrome extension that tells you which of your cards earns the most at checkout, kept current by an LLM pipeline that reads issuer terms.

- No model runs at checkout. A deterministic TypeScript engine ranks your cards in integer cents and basis points, offline, with no API key.
- The LLM drafts each card's reward rules from issuer pages, and every fact has to quote its source. Agents verify the drafts, and a person publishes each catalog release; the model has no write path.
- Measured extraction eval on real issuer terms: the best setups reach 97 to 99% field accuracy on held-out issuers, and a detailed prompt was the biggest lever (65 to 83% with a two-sentence prompt, 92 to 99% guided).

178 cards from the top 10 U.S. issuers · [Live site](https://ai-checkout-api.onrender.com/) · [Eval results](https://ai-checkout-api.onrender.com/results/)

<img src="https://skillicons.dev/icons?i=ts,react,nodejs,supabase,postgres,vite&perline=12" height="36" alt="ts, react, nodejs, supabase, postgres, vite" />

### [skills](https://github.com/evanxliu1/skills)

Agent Skills for Claude Code and other coding agents. The main one, `llm-wiki`, sets up an agent-maintained project wiki with `AGENTS.md` wiring and a dependency-free linter in CI.

<img src="icons/claude-code.svg" height="36" alt="Claude Code" /> <img src="icons/codex.svg" height="36" alt="Codex" /> <img src="icons/cursor.svg" height="36" alt="Cursor" />

### [lctmr](https://github.com/evanxliu1/lctmr)

An R package for latent class trajectory modeling of early-life growth: find subgroups of children with distinct growth patterns, with diagnostics first and model search after.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22884978.svg)](https://doi.org/10.5281/zenodo.22884978)

<img src="https://skillicons.dev/icons?i=r&perline=12" height="36" alt="r" />

### [Crash Never](https://github.com/evanxliu1/Crash-Never) (WIP)

Collision prediction from dashcam video on the Nexar dataset: YOLOv11 detection, SORT tracking, and a planned LSTM over object trajectories.

<img src="https://skillicons.dev/icons?i=python,pytorch&perline=12" height="36" alt="python, pytorch" />

---

## Contact

[LinkedIn](https://linkedin.com/in/evanxliu1) · evanliu3344@gmail.com
