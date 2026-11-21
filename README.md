# CSET485 – AI and Society · Assignment #1 (COMPAS)

**Name:** Ankit Kumar · **Roll No.:** S24BCAU0012

Stress-testing a recidivism prediction model on the ProPublica COMPAS dataset.

- Dataset: COMPAS Recidivism Risk Score Dataset (roll number ends in 2)
- Random seed: `random_state = 12` (last three digits of roll number: 012), 70 % train / 30 % test split

## Files

| File | Contents |
|---|---|
| `CSET485_Assignment1_COMPAS.ipynb` | Google Colab notebook covering data preprocessing, Part 1 (OLS vs logistic, mismatch analysis) and Part 2 (Simpson's paradox, omitted-variable bias, adversarial subset, fairness trade-off) |
| `CSET485_Assignment1_Report.pdf` | Submission report covering preprocessing, Parts 1–4 |

## How to reproduce

1. Open the notebook in Google Colab (File → Open notebook → GitHub, or use the badge below).
2. Runtime → Run all.

The notebook downloads the data directly from
`https://github.com/propublica/compas-analysis/raw/master/compas-scores-two-years.csv`.
Running it top to bottom regenerates every number, table and chart cited in the report, and saves `results.json` and `fairness_sweep.csv`.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/theankitaryan-coder/CSET485_Assignment1_COMPAS/blob/main/CSET485_Assignment1_COMPAS.ipynb)
