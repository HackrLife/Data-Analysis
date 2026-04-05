# BarcaFutbol Analytics — Yamal vs Saka

**What Do You Get When You Pit Lamine Against Saka?**
*Yamal makes you hold your breath. Saka makes you trust the moment. Football needs both.*

A complete data visualisation analysis comparing **Lamine Yamal (Age 18)** and
**Bukayo Saka (Age 24)** across 8 analytical dimensions — career arc, attacking
profile, possession and creation, defensive contribution, head-to-head metrics,
peer group scatter plots, and conversion efficiency.

Built by [BarcaFutbol](https://barcafutbol.com) · HackrLife Media LLC · April 2026

---

## View the Notebook

> GitHub does not render large notebooks directly. Use the links below.

### ▶ [View on nbviewer](https://nbviewer.org/github/HackrLife/Data-Analysis/blob/main/Yamal-vs-Saka/BarcaFutbol_Yamal_vs_Saka.ipynb)

*All 8 charts visible instantly — no code required.*

### ▶ [Open in Google Colab](https://colab.research.google.com/github/HackrLife/Data-Analysis/blob/main/Yamal-vs-Saka/BarcaFutbol_Yamal_vs_Saka.ipynb)

*Opens live in Colab. Hit Run All to regenerate every chart from scratch.*

---

## Folder Contents

```
Yamal-vs-Saka/
├── README.md                          ← this file
├── BarcaFutbol_Yamal_vs_Saka.ipynb   ← fully executed notebook (all 8 charts)
├── data/
│   └── barcafutbol_master.csv        ← master dataset (25 players, all metrics)
└── charts/                            ← pre-rendered PNGs at 300 DPI
    ├── 01_career_arc.png
    ├── 02_pizza_dual.png
    ├── 03_radar_attacking.png
    ├── 04_radar_possession.png
    ├── 05_radar_defending.png
    ├── 06_head_to_head.png
    ├── 07_scatter_creator_finisher.png
    └── 08_scatter_xg_vs_goals.png
```

---

## The 8 Charts

| # | Chart | Key Insight |
|---|-------|-------------|
| 01 | Career Arc | Yamal at 18 matches Saka's career peak at 23 |
| 02 | Full Profile Pizza | Yamal attacks at extreme volume; Saka delivers with precision |
| 03 | Attacking Radar | Yamal 92nd pct shots/90; Saka more clinical per attempt |
| 04 | Possession Radar | Yamal creates more; cross accuracy gap is the defining number |
| 05 | Defensive Radar | Saka 88th pct discipline; Yamal's defensive output declining |
| 06 | Head to Head Bar | Yamal leads 7 of 10 metrics; Saka wins both precision metrics |
| 07 | Creator vs Finisher | Yamal in dual-threat territory at 18 vs 16-player peer group |
| 08 | xG vs Goals | Yamal +0.19 above expectation; Saka exactly on the line every season |

---

## The Analytical Argument

These are not two versions of the same player. They are two answers to the same question:
*what does a world-class wide forward look like when built from the ground up?*

**Yamal** is the phenomenon — volatile, explosive, statistically unprecedented at 18.
His 1.0 G+A per 90 this season is a figure Saka reached only at his career peak at 23.
He overperforms his xG by +0.19 — consistently, across two seasons. He loses the ball
27 times per match and creates five key passes in the same 90 minutes.

**Saka** is the professional — consistent, reliable, the product of one of football's
most tactically sophisticated systems. His coefficient of variation on goals across
eight seasons is 0.57 — the most predictable elite wide forward in the peer group.
His 88th-percentile discipline means Arteta can press with him at maximum intensity
without managing his aggression. His 25/26 decline from 0.9 to 0.4 G+A per 90 at
age 24 is the most important unanswered question in the comparison.

---

## Data

All statistics sourced from **Sofascore**, per-90-minute averages, all competitions,
2025/26 season. Career data covers Yamal (4 seasons, 2022/23–2025/26) and
Saka (8 seasons, 2018/19–2025/26). Peer group: 16 top European wide forwards,
minimum 25 appearances in 25/26.

Percentile estimates in radar and pizza charts are benchmarked against La Liga /
Premier League wide forward populations and noted as estimated throughout.

All data verified against source CSVs at time of publication (April 2026).

---

## Design System

```python
BG      = '#0d1117'   # near-black background
BG2     = '#0d1b2a'   # alternate dark surface
WHITE   = '#f0f6fc'   # labels and text
GRAY    = '#8b949e'   # secondary text, grid lines
GOLD    = '#EDBB00'   # accent, reference lines
GREEN   = '#4CAF50'   # elite performance tier (≥70th pct)
YELLOW  = '#ffd60a'   # average performance tier (40–69th pct)
RED     = '#e63946'   # below average (<40th pct)
YAMAL_C = '#A50044'   # Barça deep red
SAKA_C  = '#f0f6fc'   # clean white
```

All charts output at 300 DPI. Consistent dark theme across all visualisations.

---

## Part of the HackrLife Data Analysis Repo

This folder is part of the [HackrLife Data Analysis](https://github.com/HackrLife/Data-Analysis)
repository — a growing collection of football analytics, AI governance research,
and data visualisation work.

Full article: *"What Do You Get When You Pit Lamine Against Saka?"*
Available at [barcafutbol.com](https://barcafutbol.com)

---

*© 2026 HackrLife Media LLC / BarcaFutbol. MIT licence for code. Data © Sofascore.*
