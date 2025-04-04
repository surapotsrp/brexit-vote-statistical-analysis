# 🇬🇧 Brexit Forecast using Statistical Modeling

This project explores demographic factors influencing the Brexit vote using statistical learning techniques in R. It applies clustering, logistic regression, bootstrapping, and Bayesian inference to identify key predictors and improve model stability.

📄 **Full Report:** [Brexit Forecast using Statistical Modeling (PDF)](./Brexit%20Forecast%20by%20using%20Statistical%20Modeling.pdf)

---

## 📊 Key Techniques

- **Data Exploration:** Boxplots, summary statistics, variable transformation (scaled [0–1])
- **Clustering:** K-means (K=2), Elbow Method, cluster validation with contingency table
- **Modeling Approaches:**
  - **Logistic Regression** (GLM)
  - **Bagging (Bootstrap Aggregation)** to reduce coefficient variance
  - **Bayesian Logistic Regression** using `rstanarm` for robust inference
- **Feature Selection:** Cross-validation of reduced models
- **Evaluation Metrics:** Log-likelihood, AIC, prediction plots

---

## 🔍 Key Insights

- **Strongest predictors of Brexit vote:**
  - Negative: `withHigherEd`, `medianIncome` (more education/income → remain)
  - Positive: `abc1`, `medianAge`, `notBornUK` (social class, age → leave)
- Bagging reduced coefficient variance; Bayesian regression improved log-likelihood score.
- Feature selection confirmed that all variables contribute meaningfully to model performance.

---

## 🛠 Tools Used

- **Language:** R  
- **Packages:** `ggplot2`, `dplyr`, `caret`, `rstanarm`, `e1071`, `boot`  
- **Model Types:** Logistic Regression, Bagging, Bayesian GLM  
- **Evaluation:** Contingency tables, ROC, log-likelihood comparison

---

## 👤 Author

**Surapot Nonpassopon**  
MSc Data Science and Analytics – University of Leeds  
[GitHub Portfolio](https://github.com/surapotsrp)
