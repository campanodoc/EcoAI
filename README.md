# EcoAI Framework — Website Repository

**Live site:** [www.ecoaiframework.com](https://www.ecoaiframework.com)  
**Author:** Gianfranco Rubino  
**PhD Cycle:** XXXVIII — Learning Sciences and Digital Technologies  
**Research:** *Ecoliteracy and Civic Education: a Framework for EcoAI*

---

## What this is

This repository hosts the static website for the **EcoAI Framework**, an interdisciplinary research project integrating Ecoliteracy and Artificial Intelligence literacy into civic education at the secondary school level.

The site presents the theoretical framework, two independent empirical phases for the **EcoAI Index** (exploratory N=403; confirmatory administration N=198; final CFA/SEM N=151; index and invariance N=191), and supporting scientific publications.

---

## Repository Structure

```
root/
├── index.html                    # Homepage EN
├── literacies.html               # EcoAI Literacies — EN
├── research_researcher.html      # Research & Findings — EN (researcher mode)
├── research_public_en.html       # Research & Findings — EN (general public)
├── survey.html                   # Survey page
├── privacy.html                  # Privacy policy EN
├── cookie.html                   # Cookie policy EN
├── terms.html                    # Terms EN
├── sitemap.xml
├── robot.txt
├── CNAME
├── documents/                    # PDF publications
├── images/                       # Site assets
│
└── it/                           # Italian version
    ├── index.html                # Homepage IT
    ├── literacies.html           # EcoAI Literacies — IT
    ├── research_researcher_it.html  # Ricerca e Risultati — IT (ricercatore)
    ├── research_it.html             # Ricerca e Risultati — IT (pubblico generale)
    ├── survey.html
    ├── privacy.html
    ├── cookie.html
    └── termini.html
```

---

## Research Pages — Navigation Logic

Each language has two versions of the Research page, linked by a toggle in the hero section:

| File | Language | Audience |
|------|----------|----------|
| `research_researcher.html` | EN | Researcher (CFA/SEM stats, correlation matrix) |
| `research_public_en.html` | EN | General public (plain language) |
| `it/research_researcher_it.html` | IT | Ricercatore |
| `it/research_it.html` | IT | Pubblico generale |

---

## EcoAI Index — Key Metrics

Five latent dimensions validated via CFA (DWLS estimator, N=198):

| Dimension | ω | AVE | Index weight |
|-----------|---|-----|------------|
| INFO — Eco-Digital Information Literacy | 0.662 | 0.399 | 0.160 |
| AATI — AI Awareness & Critical Attitudes | 0.791 | 0.405 | 0.215 |
| VAL — Eco-Civic Values | 0.839 | 0.519 | 0.215 |
| AGY — Eco-Digital Civic Agency | 0.776 | 0.381 | 0.181 |
| EPAS — Eco-Posthuman Agency Scale | 0.729 | 0.535 | 0.230 |

**CFA fit:** CFI=0.978 · TLI=0.975 · RMSEA=0.064 · SRMR=0.082  
**EcoAI Index (original 1–5 metric):** M=3.119, SD=0.592, range 1.911–4.632 (N=191)

---

## Publications

- Rubino, G. (2025). *Eco-Digital Posthumanism: Eco-Digital Co-Responsible Agency, Genealogy and Research Agenda.* SocArXiv. [ResearchGate](https://www.researchgate.net/publication/395580797_Eco-Digital_Posthumanism_Eco-Digital_Co-Responsible_Agency_Genealogy_and_Research_Agenda)
- Rubino, G. (forthcoming). *Ecoliteracy and Social Media: Systematic and Bibliometric Review.* MDPI.

---

## How to Update

**Add or replace a page:**  
Drop the file in the correct folder (`root/` for EN, `it/` for IT) and push. GitHub Pages deploys automatically within 1–2 minutes.

**Update the sitemap:**  
Edit `sitemap.xml` — update `<lastmod>` for modified pages and add `<url>` blocks for new ones. Then re-submit via Google Search Console → Sitemaps.

**Request re-indexing after major updates:**  
Google Search Console → URL Inspection → Request Indexing for each new or updated URL.

---

## Tech Stack

- Pure HTML/CSS — no build step, no frameworks
- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Chart.js](https://www.chartjs.org) via CDN (interactive charts on research pages)
- Google Fonts: Inter + Lora
- Hosted on GitHub Pages with custom domain via CNAME

---

*Last updated: March 2026*

