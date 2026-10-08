# Prototyping Your Personal LLM Health Agent

**A half-day, hands-on tutorial at UbiComp/ISWC 2026 — Shanghai, China, October 12, 2026, 14:00–17:30 (tentative; Shanghai time, UTC+8).**

*From Multimodal Sensing Data to Actionable Health Insights.*

Build a personal LLM health agent in your browser using the official public GLOBEM sample. Write tools, inspect the agent loop, and compare answers before and after changing a skill. An AI helper can explain the lesson and help interpret code or errors; participants run and check any suggested changes. The central question is:
*“Why have I been sleeping poorly this week?”*

Ground every claim. Catch confounds. Refuse medical advice. Stress-test the agent.

🌐 **Tutorial website:** https://llm-health-agent-tutorial.github.io/
📅 **When:** October 12, 2026 · 14:00–17:30 (tentative; Shanghai time, UTC+8)
📍 **Where:** Room 5A · Shanghai, China
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
│   ├── tutorial-overview.png  # Updated concept teaser for the public GLOBEM sample
│   ├── tutorial-teaser.png    # Retained original concept figure
│   ├── saci-teaser.png
│   ├── papers/     # Accepted SACI paper
│   └── img/       # Speaker/organizer photos and current helper preview
├── code/          # Starter repository and complete bundle links
└── data/          # Synthetic scenario + GLOBEM public-sample hybrid
```

## Getting started

Dr. Thomas Plötz (School of Interactive Computing, Georgia Institute of Technology) will give the opening talk. Panel participation is being coordinated separately.

The tentative schedule for October 12 is below (Shanghai time, UTC+8; Room 5A). It includes 70 minutes of guided hands-on practice. See the [website](https://llm-health-agent-tutorial.github.io/#schedule) for updates.

| Time | Session |
| --- | --- |
| 14:00–14:05 | Welcome & overview |
| 14:05–14:30 | Opening talk — Dr. Thomas Plötz (20-minute talk + 5-minute Q&A) |
| 14:30–14:40 | Invited talk — Dr. Xin Liu |
| 14:40–14:50 | Invited talk — Dr. Teng Han |
| 14:50–15:00 | Invited talk — Dr. Chenshu Wu |
| 15:00–15:10 | Invited talk — Dr. Edith C. H. Ngai |
| 15:10–15:30 | Hands-on I — Foundations & the agent loop |
| 15:30–16:00 | Conference coffee break |
| 16:00–16:50 | Hands-on II — Tools, skills & evaluation |
| 16:50–17:30 | Panel discussion & closing — Evaluation and safety |

**Prerequisites:** Basic Python and a laptop with an up-to-date browser. The current hands-on runs Python in the browser, with no installation or personal API key required. Participants receive a seat code for model access at the tutorial; access details will be shared separately.

The interface includes editable exercises, reference solutions, scratch cells, a function/variable browser, and an AI helper that uses the lesson and the participant’s code and recent outputs. The helper offers guidance; it does not execute or verify a fix.

Participants can export their code, edits and completed outputs as a Jupyter notebook and download the public sample and lab package. Local data tools can run independently; live model calls require available service access or adapting the connection to another provider.

## Publishing the website (GitHub Pages)

The public page shows an updated concept teaser and a current interface preview with the AI helper. The tutorial platform URL and material download links are not published yet. RSVP remains available. Legacy ZIP and PPTX assets are retained; hiding entry points does not revoke access through existing direct URLs.

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
