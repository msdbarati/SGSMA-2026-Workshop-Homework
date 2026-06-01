# SGSMA 2026 Workshop — Homework

**Anomaly Detection in Power Systems with AI**
*Masoud Barati · University of Pittsburgh*
SGSMA 2026 · Santiago de Chile · June 1–4, 2026

---

## What this is

A short (≈ 20-minute) hands-on assignment that lets workshop attendees
**earn a certificate of completion**. You will run a single Jupyter
notebook, train two tiny models on a synthetic PMU dataset, write a
few lines of your own code in two clearly-marked spots, and email me
the results.

---

## How to do it

### 1. Install requirements (one-liner)

```bash
pip install numpy scikit-learn torch matplotlib jupyter
```

### 2. Open the notebook

```bash
jupyter notebook SGSMA2026_Workshop_Homework.ipynb
```

### 3. Run every cell top-to-bottom

`Shift + Enter` on each cell, in order. Total runtime is **under one
minute on a laptop CPU**.

### 4. Fill in the two HOMEWORK cells

There are exactly two spots marked `### YOUR CODE HERE ###`:

| # | What you do |
|---|---|
| **Homework 1** | Add **one extra IF-THEN rule** to the rubric so it beats the provided baseline |
| **Homework 2** | Implement **one** of `LSTM`, `GRU`, or `Transformer` (a working LSTM template is provided as a starting point) |

### 5. Run the last cell

It prints a **Results Card** and writes `results.csv` next to the notebook.

### 6. Submit

Send me an email with:

- **Subject:** `SGSMA 2026 Homework — <your full name>`
- **To:** **masoud.barati@pitt.edu**
- **Attach:** (a) a screenshot of the Results Card and (b) the `results.csv` file

That's it — you will receive your certificate by email.

---

## Bonus

Open a pull request on this repository with your `results.csv` plus a
one-paragraph note describing your custom rubric rule. Bonus PRs are
acknowledged on the workshop slides.

---

## Files in this repo

| File | What it is |
|---|---|
| `SGSMA2026_Workshop_Homework.ipynb` | The notebook to run (this is the deliverable) |
| `README.md` | This file |
| `SGSMA2026_Workshop_AnomalyDetection_AI.pdf` | Full workshop slides |
| `SGSMA2026_Workshop_Notebook.ipynb` | Full reference notebook (optional reading, ~50 cells, covers all 7 deep models + 3 novel techniques + both LLM modes) |

---

## Trouble?

- **`ModuleNotFoundError`** — re-run the pip install line above.
- **PyTorch install issues** — use the CPU build: `pip install torch --index-url https://download.pytorch.org/whl/cpu`.
- **Cell crashes** — make sure you ran the cells *in order*. Skipping cells will leave variables undefined.
- **Stuck on the homework cells** — defaults are provided so the cell still runs even if you don't add anything. You just won't earn full credit.

Open an issue on this repo or email me. Happy to help.

— Masoud
