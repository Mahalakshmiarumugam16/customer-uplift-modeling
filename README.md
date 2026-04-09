#  Customer Targeting Optimization using Uplift Modeling

##  Overview

This project uses **Uplift Modeling (Causal Machine Learning)** to identify customers who should be targeted with marketing emails to maximize conversion and reduce unnecessary costs.

---

##  Problem Statement

Most companies send marketing emails to all customers, leading to:

*  Low conversion rates
*  High marketing costs

This project identifies customers who will respond **because of marketing**, not just naturally.

---

##  Approach

* Used **T-Learner (Two Model Approach)**
* Built:

  * Treatment Model (customers who received email)
  * Control Model (customers who did not)
* Calculated:

   **Uplift Score = Treatment Prediction − Control Prediction**

---

##  Key Features

* Data preprocessing and feature engineering
* Separate modeling for treatment & control groups
* Uplift score calculation
* Customer ranking based on impact

---

##  Results

* Identified high-impact customers for targeting
* Reduced unnecessary marketing efforts
* Enabled data-driven decision-making

---

##  Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Scikit-uplift
* Matplotlib

---

##  Business Impact

*  Reduced marketing cost
*  Increased campaign efficiency
*  Improved customer targeting

---

##  Project Link

[View Notebook](uplift_modeling_project.ipynb)

---

##  Future Improvements
- Implement Qini Curve for better evaluation
- Try advanced uplift models like X-Learner

---
