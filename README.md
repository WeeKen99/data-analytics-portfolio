# Data Analytics Portfolio: Goh Wee Ken

Coursework projects from my data science studies at **Universiti Malaya** (Faculty of Computer Science & Information Technology), covering cloud data pipelines, business intelligence dashboards, and machine learning in SAS and Python.

## Projects

| | Project | What it shows | Tools |
|---|---|---|---|
| <img src="01-renewable-energy-powerbi/images/dashboard-solar.png" width="220"> | **[Renewable Energy World Wide Analysis](01-renewable-energy-powerbi/)**<br>End-to-end cloud pipeline and interactive dashboard tracking the growth of solar, wind, hydro, biofuel and geothermal energy from 2000 to 2021. | Data engineering, ETL, BI dashboard design, pipeline performance evaluation | Google Cloud Storage, Pub/Sub, Dataprep, Dataflow, BigQuery, Power BI |
| <img src="02-breast-cancer-sas/images/validation-metrics.png" width="220"> | **[Breast Cancer Diagnosis Classification](02-breast-cancer-sas/)**<br>13 tuned configurations of three model families compared for classifying tumours as malignant or benign. Logistic Regression reached 95.8% validation accuracy. | Supervised classification, hyperparameter tuning, model comparison, overfitting diagnosis | SAS Enterprise Miner |
| <img src="03-cardiovascular-ml-python/images/roc-curve.png" width="220"> | **[Cardiovascular Disease Prediction](03-cardiovascular-ml-python/)**<br>Risk-screening model for insurance applicants, trained on 70,000 patient records. XGBoost gave the best result (AUC 0.78), and the project includes a web-app design for deployment. | OSEMN workflow, EDA and statistical testing, ensemble models, GridSearchCV, data product design | Python, pandas, scikit-learn, XGBoost, R (EDA) |

## Skills demonstrated

- **Data engineering:** layered cloud architecture (ingestion → storage → processing → analytics → visualisation), multi-file joins and schema standardisation, BigQuery loading
- **Business intelligence:** interactive Power BI dashboards with slicers, field parameters and year-on-year growth measures
- **Machine learning:** Decision Trees, Random Forest, XGBoost, Gradient Boosting, AdaBoost, Neural Networks and Logistic Regression, with hyperparameter tuning and cross-validation
- **Evaluation:** accuracy, precision, recall, specificity, F1, ROC-AUC, KS statistic, Gini, and pipeline throughput, memory and CPU metrics
- **Communication:** turning model results into business recommendations for insurance and energy stakeholders

## Repository layout

```
01-renewable-energy-powerbi/   Power BI dashboard (.pbix), architecture and evaluation charts
02-breast-cancer-sas/          SAS pipeline, results charts, full report (PDF)
03-cardiovascular-ml-python/   Jupyter notebook, requirements, EDA and model charts
```

Each folder has its own README with the problem, method, results and my contribution.

> The datasets are public Kaggle datasets and are not stored in this repository. Each project README links to its source.
