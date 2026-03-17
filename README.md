# TN_Election_Prediction_2026
A beginner-level Data Science project that predicts election seat counts for Tamil Nadu 2026 Assembly Elections using Machine Learning.

# Tamil Nadu 2026 Election Prediction

I built this project to predict which party will win in Tamil Nadu 2026 elections
using Python and Machine Learning.

---

## What This Project Does

- Takes survey data from 41 Tamil Nadu constituencies
- Cleans the messy data (missing values, wrong formats, duplicates)
- Trains a Machine Learning model to predict seats
- Shows the results as charts

---

## What I Used

- Python
- Pandas — to handle data
- Scikit-learn — for the ML model
- Matplotlib — to make charts

---

## Files

- `election_simple.py` — the main code
- `election_dataset.xlsx` — the raw data I collected
- `election_results.png` — output charts

---

## How to Run

1. Install the libraries:
```
pip install pandas scikit-learn matplotlib openpyxl
```

2. Keep `election_dataset.xlsx` and `election_simple.py` in the same folder

3. Run:
```
python election_simple.py
```

---

## Results

- NDA predicted to win — 31 constituencies
- SPA predicted to win — 10 constituencies
- Average seat prediction error — 0.78 seats

---

## Problems I Found and Fixed

- Some vote % values had a % symbol that broke the code — I fixed it
- 2 duplicate rows were in the data — I removed them
- 1 row had nda votes = 999 which is impossible — I removed it
- 1 row had negative vote % — I removed it
- 1 row was completely empty — I removed it
- Missing values were filled using median

---

## Limitations

- Only 41 constituencies (Tamil Nadu has 234 total)
- More data would give better predictions
- This is a learning project, not an actual election forecast

---

## What I Learned

- How to clean real messy data
- How Random Forest ML model works
- How to evaluate a model using R² and MAE
- How to plot results using Matplotlib

---

Made by [janisha] | Beginner Data Science Project 2026
