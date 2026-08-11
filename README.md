# Prototyping Your Personal LLM Health Agent

**A half-day, hands-on tutorial at UbiComp/ISWC 2026 — Shanghai, China, October 11, 2026 (tentative).**

*From Multimodal Sensing Data to Actionable Health Insights.*

Build a working personal LLM health agent from a minimal scaffold, over a synthetic, curated
multimodal sensing dataset (sleep, heart rate, activity, GPS, screen time, EMA), then evaluate when
its answers should and should not be trusted. The central question is still:
*“Why have I been sleeping poorly this week?”*

Ground every claim. Catch confounds. Refuse medical advice. Stress-test the agent.

🌐 **Tutorial website:** https://llm-health-agent-tutorial.github.io/
📅 **When:** UbiComp/ISWC 2026, Shanghai · Half-day (3.5h), hands-on
✉️ **Contact:** zj2445@cumc.columbia.edu

---

## What you'll build

- Health-specific tools (data retrieval, analysis, visualization) registered with an LLM agent.
- An agent loop (planning → tool selection → execution → observation → response).
- A runnable agent that answers open-ended questions over multimodal sensing data.
- A practical checklist for evaluating LLM agents on minimal faithfulness, confounds, safety handling, and user-alignment.

The hands-on format instantiates Student–AI Collaborative Inquiry (SACI); read the
[accepted UbiComp/ISWC 2026 Education Forum paper](docs/papers/saci-ubicomp-companion-2026.pdf).

## Repository layout

```
.
├── docs/          # Tutorial website (GitHub Pages source)
│   ├── index.html
│   ├── tutorial-teaser.png
│   ├── saci-teaser.png
│   ├── papers/     # Accepted SACI paper
│   └── img/       # Organizer photos
├── code/          # Starter scaffold, notebooks, reference solutions  (coming soon)
└── data/          # Fully synthetic teaching dataset                  (coming soon)
```

## Getting started

> Detailed setup instructions, including a one-command install script, will be sent to
> registered participants two weeks before the tutorial.

**Prerequisites:** Python ≥ 3.10 and Jupyter. For the full LLM-based experience, bring either an API
key for OpenAI or Gemini or a compatible local Ollama model. A key or local model is recommended,
not required: an interface-compatible deterministic scripted fallback supports the guided
tool-building and agent-wiring exercises if neither is available or setup fails, but it does not
reproduce open-ended LLM reasoning.

## Publishing the website (GitHub Pages)

1. Push this repository to GitHub.
2. Settings → Pages → Source: **Deploy from a branch** → branch `main`, folder **`/docs`** → Save.
3. The site goes live at `https://<account>.github.io/<repo>/`.
   (Optional: add a `CNAME` file in `/docs` for a custom domain.)

## Organizers

- **Zhihan Jiang** — Columbia University
- **Will Ke Wang** — Columbia University
- **Blue (Georgianna) Lin** — Columbia University
- **Brenna Li** — Stanford University
- **Xuhai “Orson” Xu** — Columbia University · Google Research

## Responsible use

This tutorial builds research prototypes for sensor-data sensemaking; it is **not** training in
clinical decision support. Outputs are exploratory, not validated medical guidance. Any deployment
on humans (including self, family, or research participants) requires appropriate IRB review.
A `RESPONSIBLE_USE.md` will ship alongside the starter code.

## License

Code and materials are released under the **MIT License** (see `LICENSE`).
