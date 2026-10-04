# Hi, I’m Evan Liu

I’m a Data Science major at UC Davis, interested in building data driven apps using ML and AI. Below are some of my favorite recent projects.

---

## Projects

### [AI Checkout](https://github.com/evanxliu1/AICheckout)

A Chrome extension that tells you which of your cards earns the most at checkout, kept current by an LLM pipeline that reads issuer terms.

- Deterministic TypeScript engine ranks your cards in integer cents and basis points, offline.
- The LLM drafts each card's reward rules from issuer pages, and every fact must cite an exact span of the source. A person reviews and publishes each catalog release; the model has no write path.
- Measured extraction eval on real issuer terms: the best setups reach 97 to 99% field accuracy on held-out issuers, and a detailed prompt was the biggest lever (65 to 83% with a two-sentence prompt, 92 to 99% guided). [Results](https://ai-checkout-api.onrender.com/results/)

178 cards from the top 10 U.S. issuers · [Live site](https://ai-checkout-api.onrender.com/)
<sub>TypeScript · React · Chrome MV3 · Fastify · Supabase Postgres · Render</sub>

### [skills](https://github.com/evanxliu1/skills)

Agent Skills for Claude Code and other coding agents. The main one, `llm-wiki`, sets up an agent-maintained project wiki with `AGENTS.md` wiring and a dependency-free linter in CI.

<sub>Python · Claude Code plugin</sub>

### [lctmr](https://github.com/evanxliu1/lctmr)

An R package for latent class trajectory modeling of early-life growth: find subgroups of children with distinct growth patterns, with diagnostics first and model search after. [DOI](https://doi.org/10.5281/zenodo.22884978)

<sub>R · lcmm · ggplot2</sub>

### [Crash Never](https://github.com/evanxliu1/Crash-Never) (paused)

Collision prediction from dashcam video on the Nexar dataset: YOLOv11 detection, SORT tracking, and a planned LSTM over object trajectories.

<sub>Python · YOLO · PyTorch</sub>

## Contact

[LinkedIn](https://linkedin.com/in/evanxliu1) · evanliu3344@gmail.com

---

## Get in Touch

- 🔗 [LinkedIn](https://linkedin.com/in/evanxliu1)  
- ✉️ evanliu3344@gmail.com 

---
