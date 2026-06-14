# Transfer Learning Short Course — Interactive Demos

Interactive companion notebook for the ICSA 2026 short course *A Selective Introduction to the Statistical Foundations of Transfer Learning* (Yang Feng, NYU; Ye Tian, Yale).

Four live simulations — one per lecture — with sliders you can drag during (or after) the talk:

1. **L1** — covariate shift vs. posterior drift (2-D scatter).
2. **L2** — distribution shift vs. target excess risk (divergence bound).
3. **L3** — importance weighting under covariate shift.
4. **L4** — biased ridge as "safe transfer" under posterior drift.

## Run it (no install)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yangfengstat/transfer-learning-short-course/blob/main/transfer_learning_demos.ipynb)

Click the badge, then **Runtime → Run all**. Drag the sliders.

## Run it locally

```
pip install -r requirements.txt
jupyter notebook transfer_learning_demos.ipynb
```
