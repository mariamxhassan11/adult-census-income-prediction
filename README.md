# Adult Census Income Classification

Demographic and socioeconomic binary classification model predicting whether annual individual income exceeds $50K.

## Project Structure

```text
02_Adult_Census_Income/
├── adult_census_income_data.csv
├── adult_census_income_pipeline.ipynb
├── app.py
├── best_model.pkl
├── model_metadata.json
├── requirements.txt
└── README.md
```

## Dataset & Features

- **Dataset File:** `adult_census_income_data.csv`
- **Task Type:** `Classification`
- **Target Variable:** `income_above_50k`
- **Numerical Features (4):** `age, education_num, capital_gain, hours_per_week`
- **Categorical Features (5):** `workclass, education, marital_status, occupation, sex`

## Model Evaluation Summary

- **Selected Best Model:** `LogisticRegression`

| Metric | Score |
| :--- | :--- |
| `accuracy` | `0.9333` |
| `f1_score` | `0.8929` |
| `roc_auc` | `0.974` |

## Quickstart & Deployment

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Streamlit web application:
   ```bash
   streamlit run app.py
   ```
