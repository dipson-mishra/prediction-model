# La Liga Match Prediction with Machine Learning

Personal project working through a full data science pipeline on La Liga football match predictions. Built from scratch with public data.

---

## Where I'm At

- **Part 1: Data Loading & Exploration** — done ✅
- **Part 2: Feature Engineering & Preprocessing** — done ✅
- **Part 3: Model Training & Evaluation** — done ✅
- **Part 4: Performance Check & Iteration** — done ✅

## The Data

Historical match dataset containing fixture details, team statistics, venue, match reports, and metadata.

---

## Part 1: Data Loading & Exploration ✅

Imported match statistics and inspected shape, columns, and data distributions across multiple seasons to understand historical win rates, home advantage, and team performance metrics.

---

## Part 2: Feature Engineering & Preprocessing ✅

Encoded categorical variables such as match venue, opponent codes, match times, and days of the week into numeric features. Prepared training and testing subsets split by chronological seasons.

---

## Part 3: Model Training & Evaluation ✅

- **Approach**: Built a **Random Forest Classifier** (`RandomForestClassifier`) using `scikit-learn`.
- **How it works**: 
  The model trains on historical match attributes prior to target seasons, learning patterns from venue codes, team codes, and temporal features to classify match outcomes (Wins vs. Non-Wins).
- **Evaluation**: Quantified performance using precision, recall, and accuracy metrics.

---

## Part 4: Performance Check & Iteration 📊

**Current Status:**
- Baseline established using Random Forest on core categorical and temporal features.
- Evaluating classification thresholds and feature importance to isolate key predictive signals.

**Most likely areas for improvement:**
- Incorporating rolling team form (e.g., last 5 matches goal difference, rolling average goals scored/conceded).
- Adding head-to-head historical statistics between specific club pairings.
- Experimenting with gradient-boosted models (XGBoost, LightGBM) to capture complex non-linear interactions.

---

## Tools Used

Python, pandas, numpy, scikit-learn, Jupyter Notebook

---

## What's Next

- Advanced rolling-average feature engineering to capture team momentum and form.
- Exploring hyperparameter tuning and gradient-boosting algorithms to boost prediction accuracy.
README.md
Displaying README.md.
