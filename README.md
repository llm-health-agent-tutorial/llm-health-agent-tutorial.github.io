# Prototyping Your Personal LLM Health Agent

**A half-day, hands-on tutorial at UbiComp/ISWC 2026 — Shanghai, China, October 11–15, 2026.**

*From Multimodal Sensing Data to Actionable Health Insights.*

Build a working personal LLM health agent from a minimal scaffold, over a synthetic, curated
multimodal sensing dataset (sleep, heart rate, activity, GPS, screen time, EMA), and turn raw
sensor streams into grounded, personalized answers to questions like
*“Why have I been sleeping poorly this week?”*

🌐 **Tutorial website:** _(GitHub Pages on `/docs` — see "Publishing the website" below)_
📅 **When:** UbiComp/ISWC 2026, Shanghai · Half-day (3.5h), hands-on
✉️ **Contact:** zj2445@cumc.columbia.edu

---

## What you'll build

- Health-specific tools (data retrieval, analysis, visualization) registered with an LLM agent.
- An agent loop (planning → tool selection → execution → observation → response).
- A runnable agent that answers open-ended questions over multimodal sensing data.
- A practical checklist for evaluating LLM agents on faithfulness, safety, and user-alignment.

## Repository layout

```
.
├── docs/          # Tutorial website (GitHub Pages source)
│   ├── index.html
│   ├── teaser.png
│   └── img/       # Organizer photos
├── code/          # Starter scaffold, notebooks, reference solutions  (coming soon)
└── data/          # Synthetic, de-identified teaching dataset         (coming soon)
```

## Getting started

> Detailed setup instructions, including a one-command install script, will be sent to
> registered participants two weeks before the tutorial.

**Prerequisites:** Python ≥ 3.10, Jupyter, and either (a) an API key for a supported provider
(a small free-tier credit option will be available) or (b) a local open-weights model (e.g., via Ollama).

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
- **Xuhai “Orson” Xu** — Columbia University

## Responsible use

This tutorial builds research prototypes for sensor-data sensemaking; it is **not** training in
clinical decision support. Outputs are exploratory, not validated medical guidance. Any deployment
on humans (including self, family, or research participants) requires appropriate IRB review.
A `RESPONSIBLE_USE.md` will ship alongside the starter code.

## License

Code and materials are released under the **MIT License** (see `LICENSE`).
