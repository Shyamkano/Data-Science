# 🕵️ Hypothesis Testing (Stranger Things Case Study)

This directory focuses on making statistical inferences using real-world data. We analyze the script of the TV show **Stranger Things** to answer questions about dialogue length and character interactions.

## 📓 Notebooks

### `Hypothesis_Testing_StrangerThings.ipynb`
A complete walkthrough of statistical testing using the `stranger_things_all_dialogue.csv` dataset.

**Tests Covered:**
1.  **One-Sample T-test:** Testing if the average dialogue length equals a specific value (5 words).
2.  **Two-Sample Independent T-test:** Comparing dialogue lengths between **Season 1 vs. Season 2**.
3.  **Paired T-test:** Comparing dialogue length in the *first half* vs. *second half* of episodes.
4.  **Chi-Square Test:** Checking independence between **Season** and **Dialogue Presence** (Stage directions vs. Spoken lines).

## 📊 Key Findings
- We determined if the writing style (sentence length) changed significantly between seasons.
- We analyzed if episodes become "less talkative" towards the end using paired testing.
