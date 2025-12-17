# 📉 Analysis of Variance (ANOVA)

This folder contains practical implementations of ANOVA to compare means across multiple groups statistically.

## 📓 Notebooks

### `anova.ipynb`
Using the **Stranger Things** dataset, we go beyond simple t-tests to compare multiple seasons simultaneously.

**Techniques Applied:**
- **One-way ANOVA (F-test):** Testing if mean dialogue lengths differ across Season 1, 2, 3, and 4.
- **Two-way ANOVA:** Analyzing the simultaneous effect of two factors:
    1. `Season`
    2. `Episode Group` (Early vs. Late episodes)
    - *Includes Interaction Effects (Does the effect of being an "early episode" depend on which season it is?)*

## 🧠 Key Concepts
- **F-Statistic:** Measuring the ratio of variance between groups vs. within groups.
- **P-Value Interpretation:** Deciding when to reject the Null Hypothesis.
- **OLS Models:** Using `statsmodels.formula.api` for linear modeling.
