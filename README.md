# Spambase — Spam Classification Project

A project to build, evaluate, and analyze models that classify email messages as spam or non‑spam using the UCI Spambase dataset.  
(Original dataset: UCI Machine Learning Repository) ([github.com](https://github.com/Pavel-Surkov/spambase))

---

## Table of Contents

1. [Motivation](#motivation)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Setup & Requirements](#setup--requirements)
5. [Results Summary](#results-summary)
6. [License](#license)

---

## Motivation

- Spam filtering is a practical and classic binary classification problem.
- This project is meant as both a learning exercise and a demonstration of how different models perform on a well-known dataset.

---

## Dataset

- Based on the **Spambase** dataset from UCI (https://archive.ics.uci.edu/dataset/94/spambase) ([github.com](https://github.com/Pavel-Surkov/spambase))
- Contains features extracted from email messages (word frequencies, character frequencies, etc.)
- Binary labels: spam (1) vs non‑spam (0)

The dataset is included (or expected under `data/` folder) in this repo.

---

## Project Structure

Here’s a rough outline of the repository:

```
.
├── data/                        # raw / processed datasets
├── notebooks/                   # exploratory notebooks, analysis
│   ├── EDA.ipynb
│   ├── modeling.ipynb
│   └── evaluation.ipynb
├── .gitignore
├── requirements.txt
└── README.md
```

You may also have model output files, serialized models, or logs depending on how you extend it.

---

## Setup & Requirements

1. Clone the repo:

   ```bash
   git clone https://github.com/Pavel-Surkov/spambase.git
   cd spambase
   ```

2. (Optional) Create & activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

Make sure you have the dataset in `data/`, or adjust paths in notebooks accordingly.

---

## Results Summary

Best model: Neural Network Tensorflow model with total accuracy 0.93

---

## License

MIT
