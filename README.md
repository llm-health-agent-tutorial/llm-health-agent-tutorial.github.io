# Prototyping Your Personal LLM Health Agent

**A half-day, hands-on tutorial at UbiComp/ISWC 2026 — Shanghai, China, October 12, 2026, 14:00–17:30 (tentative; Shanghai time, UTC+8).**

*From Multimodal Sensing Data to Actionable Health Insights.*

Build a working personal LLM health agent from a minimal scaffold, using the official public GLOBEM sample with labeled synthetic supplements as the main exercise, plus a separate synthetic confound scenario, then evaluate when
its answers should and should not be trusted. The central question is still:
*“Why have I been sleeping poorly this week?”*

Ground every claim. Catch confounds. Refuse medical advice. Stress-test the agent.

🌐 **Tutorial website:** https://llm-health-agent-tutorial.github.io/
📅 **When:** October 12, 2026 · 14:00–17:30 (tentative; Shanghai time, UTC+8)
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
├── code/          # Starter repository and complete bundle links
└── data/          # Synthetic scenario + GLOBEM public-sample hybrid
```

## Getting started

Thomas Plötz (School of Interactive Computing, Georgia Institute of Technology) will give the opening talk. Panel participation is being coordinated separately.

The tentative afternoon remains October 12, 14:00–17:30, with the conference coffee break at 15:30–16:00. The detailed timetable is being updated to accommodate the opening talk, invited talks, hands-on teaching, and the closing panel on evaluation and safety. Individual session times and speaking order will be announced on the [website](https://llm-health-agent-tutorial.github.io/#schedule).

> Detailed setup instructions, including a one-command install script, will be sent to
> registered participants two weeks before the tutorial.

**Prerequisites:** Python 3.10–3.12 and Jupyter. For the full LLM-based experience, prefer a prepared local Ollama model. An OpenAI or Gemini API backend is an optional alternative. A key or local model is recommended,
not required: an interface-compatible deterministic scripted fallback supports the guided
tool-building and agent-wiring exercises if neither is available or setup fails, but it does not
reproduce open-ended LLM reasoning.

## Publishing the website (GitHub Pages)

Starter repository, materials bundle and teaching slides links are temporarily hidden on the website while the materials are finalized. RSVP remains available. The repository, ZIP and PPTX are retained; this only hides the website entry points, not access through existing direct URLs. Restore the hero button, materials links and resource row in `docs/index.html` when the materials are ready.

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
The starter code includes `RESPONSIBLE_USE.md` and a participant privacy checklist.

## License

Original tutorial code and materials use the **MIT License** (see `LICENSE`). The GLOBEM public sample retains upstream Apache-2.0 notices.
