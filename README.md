# Muneera Mohamed

**Applied data science for financial and operational decisions**

MSc Data Science · CMA (USA) · CA (Professional Education II) · 8+ years in financial analysis, FP&A and business analytics · Abu Dhabi, UAE

I build machine-learning and forecasting models and connect them to the decision they support: what gets prioritised, what it costs, and what the risk is. My background in management accounting shapes how I frame problems. I start from the decision and the cost of each type of error, and choose the validation and the metric to match.

---

## Projects

| Project | Problem | Methods | Result |
| :--- | :--- | :--- | :--- |
| [Hotel Review Sentiment](https://github.com/Muneera-DSA/Hotel-Review-Sentiment-Analysis) | Flag unhappy guests from 515K hotel reviews so a team can prioritise responses | TF-IDF + logistic regression · hotel-grouped validation · significance tests · SHAP · model card | Catches 81% of unhappy guests by reading 7.2% of reviews (PR-AUC 0.849 on unseen hotels) |
| [BrainGuard: brain-tumour MRI](https://github.com/Muneera-DSA/BrainGuard-MRI-Tumor-Detection) | Are published 95–99% MRI accuracies real? Audit a popular benchmark, then build a classifier validated on unseen patients | Duplicate & patient-overlap audit · EfficientNetB0 · patient-grouped CV · 7 Holm-corrected hypothesis tests · robustness · SHAP & Grad-CAM tested against tumour masks | Found 54% of the benchmark's test images duplicated in training. Showed leakage inflates accuracy by 5–6 points; honest tumour-type accuracy on unseen patients is 86.5% (balanced) |
| [COVID-19 Mortality Risk](https://github.com/Muneera-DSA/COVID19-Mortality-Risk) | Which confirmed COVID-19 patients should be prioritised at first attendance? Audit of my capstone model, then a rebuild on Mexico's national records (3.9M patients) | Data-quality tests · EDA · 15-model CV screen · tuned gradient boosting · trained on 2020, tested on 2021 · each state held out · leakage and imbalance tests · calibration monitoring · SHAP · model card | On 2.4M later-year patients: ROC-AUC 0.949, well calibrated; the 10% highest-risk patients include 78% of deaths. Showed the original model was trained on a distorted sample (55% vs 21% death rate) with leaked variables, overestimating risk by about 40% |

More projects are being prepared for publication with code, data instructions and reproducible results:

- **Heart disease risk:** explainable classification on clinical features
- **Retail demand forecasting:** time-series forecasting linked to inventory decisions

---

## Skills

**Data science & ML:** Python (pandas, NumPy, scikit-learn), statistical analysis and hypothesis testing, classification, time-series forecasting, feature engineering, model validation, explainability (SHAP, Grad-CAM), deep learning (CNNs)

**Analytics & BI:** SQL, advanced Excel, Power BI (DAX), Tableau, Looker Studio, KPI design and management reporting

**Finance:** FP&A, budgeting and forecasting, variance and cost analysis, cash-flow analysis, financial modelling and valuation, feasibility studies and business cases

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Contact

Open to data science, analytics and FP&A-analytics roles.

[LinkedIn](https://linkedin.com/in/muneera-mohamed-7010ba109)
