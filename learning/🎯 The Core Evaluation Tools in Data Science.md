# 🎯 The Core Evaluation Tools in Data Science

This section summarizes the essential tools used to evaluate machine learning models across real-world data science workflows.

**Goals:**
- Understand the primary libraries used for model evaluation  
- Identify which tools support metrics, visualization, interpretability, and monitoring  
- Build a reusable mental model for evaluating any ML model  
- Provide a clean reference for future projects and pipelines

This document is part of a broader ML workflow and portfolio structure.

---

## 🧰 1. Scikit-Learn (sklearn.metrics)
**Use for:** Classification, regression, clustering metrics; confusion matrices; ROC/PR curves; cross-validation  
**Why it matters:** The default evaluation engine for most DS workflows.

---

## 📈 2. Matplotlib / Seaborn
**Use for:** Confusion matrices, ROC curves, PR curves, residual plots, error distributions  
**Why it matters:** Evaluation is visual — these are the core plotting tools.

---

## 📊 3. Plotly
**Use for:** Interactive ROC/PR curves, hoverable confusion matrices, feature importance dashboards  
**Why it matters:** Stakeholders prefer interactive, explorable visuals.

---

## 🔍 4. SHAP (SHapley Additive exPlanations)
**Use for:** Feature importance, local explanations, global explanations, model debugging  
**Why it matters:** The gold standard for interpretability in modern ML.

---

## 🧠 5. LIME
**Use for:** Local interpretability and explaining individual predictions  
**Why it matters:** Still widely used in regulated industries.

---

## 🧪 6. Cross-Validation Tools
**Use for:** K-Fold, Stratified K-Fold, TimeSeriesSplit, GroupKFold  
**Why it matters:** Proper evaluation requires proper CV.

---

## 📦 7. Statsmodels
**Use for:** Regression diagnostics, p-values, confidence intervals, AIC/BIC  
**Why it matters:** Adds statistical rigor beyond ML metrics.

---

## 🧱 8. MLflow
**Use for:** Experiment tracking, metric logging, model comparison, artifact storage  
**Why it matters:** Essential for reproducibility in enterprise workflows.

---

## 📉 9. TensorBoard
**Use for:** Loss curves, accuracy curves, embedding visualizations, hyperparameter tracking  
**Why it matters:** Deep learning requires specialized monitoring.

---

## 🧭 10. Yellowbrick
**Use for:** ROC/PR curves, residual plots, feature importance, class balance, learning curves  
**Why it matters:** Built specifically for model evaluation and integrates with sklearn.

---

## 🧪 11. Great Expectations
**Use for:** Data validation, schema checks, drift detection  
**Why it matters:** Evaluation starts with data quality.

---

## 🧩 12. Evidently AI
**Use for:** Drift detection, data quality reports, model performance dashboards  
**Why it matters:** Production evaluation is continuous.

---

# 🧠 Summary Mental Model

### The core tools you will use repeatedly:
**sklearn.metrics, Matplotlib/Seaborn, SHAP, MLflow, Statsmodels**

Everything else supports specialized evaluation needs.

