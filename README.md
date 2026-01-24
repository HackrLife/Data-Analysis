# Data-Analysis

**Data journalism meets rigorous analysis.**

A collection of data stories that combine multiple datasets to uncover insights invisible in any single chart. Each project transforms raw data into narrative-driven analysis with custom visualizations, derived metrics, and strategic implications.

---

## What This Repository Is

This is not a collection of charts. It's a portfolio of **data storytelling projects** — each one:

- Combines multiple datasets to reveal hidden patterns
- Creates derived metrics that don't exist in source data
- Tells a coherent narrative with beginning, middle, and end
- Delivers actionable insights for practitioners
- Includes reproducible Python code in Jupyter notebooks

**Domains covered:** Marketing · Football Analytics · Market Intelligence · Business Strategy

**Data sources:** EMARKETER · Wyscout · Statista · Kaggle · Google Trends · Public APIs

---

## Methodology

Each project follows a consistent analytical framework:

```
┌─────────────────────────────────────────────────────────────────┐
│  1. DATA COLLECTION                                              │
│     Multiple sources → Clean → Normalize → Validate              │
├─────────────────────────────────────────────────────────────────┤
│  2. DERIVED METRICS                                              │
│     Combine datasets → Calculate new metrics → Reveal hidden     │
│     patterns that don't exist in any single source               │
├─────────────────────────────────────────────────────────────────┤
│  3. NARRATIVE STRUCTURE                                          │
│     Find the story arc → Identify the paradox/insight →          │
│     Structure as beginning/middle/end                            │
├─────────────────────────────────────────────────────────────────┤
│  4. VISUALIZATION                                                │
│     Design charts that reveal, not just display →                │
│     Annotate key moments → Use consistent visual language        │
├─────────────────────────────────────────────────────────────────┤
│  5. STRATEGIC IMPLICATIONS                                       │
│     So what? → Actionable recommendations →                      │
│     Audience-specific insights                                   │
└─────────────────────────────────────────────────────────────────┘
```

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.10+** | Core analysis |
| **pandas** | Data manipulation |
| **NumPy** | Numerical operations |
| **matplotlib** | Custom visualizations |
| **seaborn** | Statistical graphics |
| **Jupyter** | Reproducible notebooks |
| **python-docx** | Report generation |

---

## Repository Structure

```
data-visualizations/
│
├── README.md                          # This file
│
├── mobile-video-ad-paradox/           # Project 1
│   ├── README.md                      # Project overview
│   ├── EXECUTIVE_SUMMARY.md           # Key findings
│   ├── Mobile_Video_Ad_Data_Story.ipynb  # Main notebook
│   ├── The_145_Billion_Paradox_Report.docx
│   ├── data/                          # Source CSVs
│   └── visualizations/                # Generated PNGs
│
├── football-tactics/                  # Project 2 (coming soon)
│   └── ...
│
├── cloud-market-intelligence/         # Project 3 (coming soon)
│   └── ...
│
└── templates/                         # Reusable templates
    ├── visualization_style.py         # Dark theme config
    └── notebook_template.ipynb        # Starter notebook
```

---

## Visual Language

All projects use a consistent dark theme optimized for readability and impact:

| Element | Color | Hex |
|---------|-------|-----|
| Primary | Cyan | `#00D4FF` |
| Secondary | Coral | `#FF6B6B` |
| Accent | Teal | `#4ECDC4` |
| Warning | Yellow | `#FFE66D` |
| Purple | Purple | `#A855F7` |
| Green | Green | `#22C55E` |
| Background | Near Black | `#0A0A0A` |

---

## Philosophy

### Why Data Storytelling?

Raw data doesn't change minds. Stories do.

The best analysis in the world is worthless if it sits in a spreadsheet. These projects are designed to:

1. **Reveal, not just display** — Every visualization should make you see something you couldn't see before
2. **Combine to discover** — The most interesting insights emerge when you combine datasets that weren't meant to be combined
3. **Narrate, not just analyze** — Data has characters (metrics), conflict (paradoxes), and resolution (insights)
4. **Imply action** — Every analysis should answer "so what?" with specific recommendations

### Academic Rigor Meets Practical Application

This work bridges two worlds:

- **Academic:** Methodological transparency, reproducible code, cited sources, derived metrics with clear formulas
- **Practical:** Actionable insights, strategic recommendations, executive summaries, visual impact

---

## 👤 About the Author

**Dev Das**

I lead cloud GTM and Product Marketing for Google in JAPAC. Prior to this I have done simialr roles across , Adobe, SAP, LinkedIn, and IBM. Currently thinking of doing a doctoral research in AI governance while building data-driven content across marketing, football analytics, and market intelligence.

- 📧 Newsletter: [HackrLife Daily](https://hackrlife.com) — AI tools and growth marketing
- ⚽ Newsletter: [The Barça Weekly](https://barcafutbol.com) — Tactical football analysis
- 🔗 LinkedIn: [Connect](https://linkedin.com/in/devdulal)

---

## License

Code: MIT License — free to use, modify, and distribute with attribution.

Data: Subject to original source terms (EMARKETER, Wyscout, Statista, Kaggle). See individual project READMEs for specific data licensing.

Visualizations: CC BY 4.0 — free to share with attribution.

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/hackrlife/data-visualizations.git

# Navigate to a project
cd data-visualizations/mobile-video-ad-paradox

# Install dependencies
pip install pandas numpy matplotlib seaborn python-docx jupyter

# Launch Jupyter
jupyter notebook Mobile_Video_Ad_Data_Story.ipynb
```

---

## Contributing

Found an interesting dataset? Have a story idea? Open an issue or submit a PR.

**What makes a good contribution:**
- Combines multiple data sources
- Reveals a non-obvious insight
- Tells a coherent story
- Includes reproducible code

---

## ⭐ Star This Repo

If you find these data stories useful, star the repo to help others discover it.


