# Muneera Mohamed

**Applied data science for financial and operational decisions**

MSc Data Science · CMA (USA) · CA (Professional Education II) · 8+ years in financial analysis, FP&A and business analytics · Abu Dhabi, UAE · [Portfolio](https://muneera-dsa.github.io)

I build machine-learning and forecasting models and connect them to the decision they support: what gets prioritised, what it costs, and what the risk is. My background in Financial Planning & Analysis and management accounting shapes how I frame problems. I start from the decision and the cost of each type of error, and choose the validation and the metric to match.

---

## Projects

| Project | What I built | Methods | Result |
| :--- | :--- | :--- | :--- |
| [Hotel Review Sentiment](https://github.com/Muneera-DSA/Hotel-Review-Sentiment-Analysis) | A text classifier that flags unhappy guests in 515K hotel reviews so a guest-relations team can prioritise responses | TF-IDF + logistic regression · 11-model screen · hotel-grouped validation · significance tests · SHAP · model card | PR-AUC 0.849 on 299 unseen hotels (no-skill 0.065); catches 81% of unhappy guests by reading 7.2% of reviews |
| [BrainGuard: brain-tumour MRI](https://github.com/Muneera-DSA/brainguard-mri-tumor-detection) | A deep-learning classifier that identifies tumour type (glioma, meningioma, pituitary) from one MRI slice, validated on patients it never saw | Transfer learning (TensorFlow/Keras) · 6-architecture screen on identical folds · patient-grouped CV · Holm-corrected hypothesis tests · robustness to 12 image changes · SHAP & Grad-CAM scored against tumour masks · benchmark leakage audit | ResNet50: 90.1% balanced accuracy, macro AUC 0.983 on 233 unseen patients; +3.7 points over EfficientNetB0, confirmed in a second run. Showed the popular Kaggle benchmark has 54% of test images duplicated in training |
| [COVID-19 Mortality Risk](https://github.com/Muneera-DSA/COVID19-Mortality-Risk) | A 30-day mortality risk model that prioritises confirmed COVID-19 patients at first attendance, built on Mexico's national records (3.9M patients) | Data-quality tests · EDA · 15-model CV screen · tuned gradient boosting · trained on 2020, tested on 2021 · each state held out · leakage and imbalance tests · calibration monitoring · SHAP · model card | ROC-AUC 0.949 on 2.4M patients from a later year; the 10% highest-risk patients include 78% of deaths; well calibrated (5.8% predicted vs 5.7% observed); median ROC-AUC 0.927 across 32 held-out states |
| [Cardiovascular Risk Prediction](https://github.com/Muneera-DSA/Cardiovascular-Risk-Prediction) | A 10-year cardiovascular mortality risk model for US adults, benchmarked against the clinical standard (ACC/AHA Pooled Cohort Equations) | NHANES 1999–2018 linked to the National Death Index (23,888 adults) · data-quality tests · 18-model CV screen (incl. XGBoost, LightGBM) · temporal validation · Cox survival model · calibration & decision curves · SHAP · model card | ROC-AUC 0.822 vs 0.799 for the clinical equations on a later period, with near-perfect calibration (observed/expected 1.01 vs 0.26); the top 10% by risk captures 47% of cardiovascular deaths |
| [Retail Demand Forecasting](https://github.com/Muneera-DSA/retail-demand-optimization) | Demand-forecasting models for three retail planning decisions (weekly ordering, store replenishment, hourly staffing), each judged on the decision it feeds | 2,283 daily and hourly series (TCS iON, Favorita, hourly demand) · data-quality checks · time-ordered CV · 14-model screens incl. Croston/SBA/TSB · benchmarked against ARIMA, SARIMA, Holt-Winters and Prophet · quantile models · Diebold-Mariano and bootstrap tests · own exact TreeSHAP · model card | Weekly orders need 10% less stock than the best rule of thumb at a 95% fill rate (CI 6–17%); staffing plan 7% cheaper than the best rule-based plan; daily forecast error (WAPE) 16.1–16.3% vs 20.7% for last week's sales across 1,782 store × family series |
| [Smart-Home Anomaly Detection](https://github.com/Muneera-DSA/smart_home_anomaly_detection) | An anomaly detector for smart-home appliance functioning: it watches smart-plug (IoT) power sensors and alerts when an appliance stops behaving normally; validated on fridges and freezers (compressors stuck on or cycling abnormally) in homes it never saw | REFIT: 20 UK homes, 129M sensor readings, 243 researcher-annotated anomalies · label clock and data-outage audit · past-only features · leave-houses-out CV · rules vs Isolation Forest vs 4 supervised models at a fixed false-alarm budget · ablation · Holm-corrected tests · exact TreeSHAP · model card | Gradient boosting caught 86% of anomalies (210/243) at 0.86 false alerts per appliance-month vs 78% for a compressor-on timer rule, and alerted earlier on the anomalies both caught (median 2.2 h vs 3.0 h); separates frozen sensors from real anomalies (AUC 0.98) |

---

## Skills

**Data science & ML:** Python (pandas, NumPy, scikit-learn, statsmodels), statistical analysis and hypothesis testing, classification, time-series forecasting (ARIMA, SARIMA, Holt-Winters, Prophet, quantile models), anomaly detection (IoT sensor data), survival analysis, feature engineering, model validation, explainability (SHAP, Grad-CAM), deep learning (CNNs)

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

**Portfolio:** [muneera-dsa.github.io](https://muneera-dsa.github.io) · **LinkedIn:** [muneera-mohamed](https://linkedin.com/in/muneera-mohamed-7010ba109) · **Email:** [munee.mohamed@gmail.com](mailto:munee.mohamed@gmail.com)
