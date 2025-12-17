# ⚙️ Feature Engineering & Scaling

Machine Learning models require clean, scaled, and numerical data. This directory covers the essential preprocessing steps to convert raw messy data into a model-ready format.

## 📓 Notebooks

### 1. `Feature Scaling and Dummification (numerical).ipynb`
Focuses on handling continuous variables using the **World Bank Dataset** and **Lung Cancer Survey**.
- **MinMax Scaling:** Rescaling features to [0, 1].
- **StandardScaler:** Transforming data to mean=0, std=1.
- **RobustScaler:** Handling outliers by scaling based on percentiles.
- **Normalization:** L1 and L2 normalization for row-based scaling.
- **Clustering:** Using K-Means to group countries based on CO2 emissions and GDP.

### 2. `Feature Scaling and Dummification (categorical).ipynb`
Focuses on converting text labels into numbers using `cardata.csv`.
- **One-Hot Encoding:** Using `LabelBinarizer` and `MultiLabelBinarizer`.
- **Ordinal Encoding:** Mapping ordered categories (e.g., Low < Medium < High).
- **Dictionary Vectorization:** Handling JSON-like feature lists.
- **Imputation:** Handling missing values using **KNN Imputer** (predicting missing values based on neighbors) and **Simple Mean/Mode Imputation**.
- **Class Imbalance:** Strategies for downsampling majority classes and upsampling minority classes.
