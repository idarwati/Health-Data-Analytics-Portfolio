## 5. Statistical Hypothesis Testing (Risk Factor Analysis)
To validate the relationships between clinical variables, I performed inferential statistical tests using `Scipy`.

### A. Intraocular Pressure (IOP) & Glaucoma Diagnosis
* **Objective:** To determine if IOP is a valid differentiator for Glaucoma.
* **Method:** Independent T-Test (Continuous vs Categorical).
* **Result:** P-Value < 0.05 ($1.32 \times 10^{-41}$).
* **Insight:** There is a statistically significant difference in mean IOP between Glaucoma and Normal patients. Patients with Glaucoma have a significantly higher mean IOP (~20.4 mmHg) compared to Normal patients (~16.8 mmHg).
* **Recommendation:** IOP screening remains a critical "first-line" filter for Glaucoma detection in our hospital.

### B. Diabetes & Diabetic Retinopathy
* **Objective:** To assess the association between Diabetes history and Retinopathy incidence.
* **Method:** Chi-Square Test of Independence.
* **Result:** P-Value < 0.05 ($2.52 \times 10^{-31}$).
* **Insight:** A strong dependency exists between Diabetes and Retinopathy. Diabetic patients show a disproportionately higher rate of positive Retinopathy compared to non-diabetics.
* **Recommendation:** Implementation of mandatory fundus screening protocols for all patients with a history of Diabetes is statistically justified to catch early-stage Retinopathy.
