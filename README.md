## About Me

I am a **3rd-year Computer Science undergraduate** (B.Tech in CSE – AI & ML) at the **Institute of Engineering & Management (IEM), Kolkata**, with a strong academic focus on **Theoretical Computer Science, Cryptography**, and **Machine Learning for scientific applications**.

I am currently working as a **Research Apprenticeship student under Prof. Dr. Avishek Adhikary** (Department of Mathematics, **Presidency University, Kolkata**), where my work centers on **Visual Cryptography and Secret Image Sharing (SIS)**. My research involves:

* Re-implementing classical SIS and Visual Cryptography schemes,
* Designing **lossless (k, n) and (t, k, n) Shamir-based image secret sharing** using finite-field arithmetic,
* Extending SIS to **Regional Secret Image Sharing** by integrating **image segmentation and deep-learning-based inpainting (LaMa)**.

Alongside cryptography, I actively work on **machine learning for Earth and climate sciences**, particularly **short-term temperature forecasting with explainable and probabilistic ML models**.

Looking ahead, I aim to pursue **doctoral studies (Ph.D.)**, with the long-term goal of becoming a **research-oriented academic and professor**, focusing on rigorous theory-backed, application-relevant computer science. 👨🏼‍🏫

---

## Selected Publications

**STAT-X: Short-term Atmospheric Temperature Forecasting using Machine Learning with Explainable-AI**
*A. Sarkar, D. Guha Roy, P. Datta*
**Theoretical and Applied Climatology**, Springer, 2025
DOI: [https://doi.org/10.1007/s00704-025-05693-8](https://doi.org/10.1007/s00704-025-05693-8)

**AgroGenie: A Smart Approach to Agriculture Using Machine Learning**
*A. Sarkar, K. Ganguly, S. Ghosh, D. Ghosh, S. Saha, P. Datta, D. Guha Roy*
**Lecture Notes in Networks and Systems**, Springer, 2024
DOI: [https://doi.org/10.1007/978-981-97-9839-1_17](https://doi.org/10.1007/978-981-97-9839-1_17)

**An Overview of the Discrete Logarithm Problem in Cryptography**
*A. Sarkar, D. Guha Roy, P. Datta*
**Lecture Notes in Networks and Systems**, Springer, 2024
DOI: [https://doi.org/10.1007/978-981-97-4799-3_10](https://doi.org/10.1007/978-981-97-4799-3_10)

---

## Manuscripts Under Preparation

**Probabilistic Short-Term Temperature Forecasting using Tuned Natural Gradient Boosting Regressor**
*A. Sarkar, D. Guha Roy, P. Datta*
Manuscript under preparation.

---

## Projects

### Short-Term Temperature Prediction using Machine Learning with Explainable-AI (STAT-X)

**Tech:** Python, scikit-learn, NGBoost, SHAP, LIME
**Repo:** [https://github.com/Abhiroop2004/STAT-X](https://github.com/Abhiroop2004/STAT-X)

* Developed supervised ML pipelines for **short-term minimum and maximum temperature forecasting** using multivariate meteorological data.
* Performed extensive **feature engineering** and evaluated **six ML models**, with **Gradient Boosting Regressor** and **MLP** achieving the best performance.
* Applied **explainable AI (SHAP, LIME)** to identify dominant climatic drivers, improving interpretability and scientific usability.
* Published in **Springer (Theoretical and Applied Climatology)**.
* Extended the framework to **probabilistic forecasting** using **NGBoost**, jointly predicting **mean and uncertainty**, with Bayesian hyperparameter tuning and cross-city robustness analysis.

---

### AgroGenie: Crop Recommendation using Machine Learning

**Tech:** Python, scikit-learn, NumPy, Pandas
**Repo:** [https://github.com/Abhiroop2004/AgroGenie-A-Smart-approach-to-Agriculture-using-Machine-Learning-](https://github.com/Abhiroop2004/AgroGenie-A-Smart-approach-to-Agriculture-using-Machine-Learning-)

* Led a team of five to develop a **machine-learning-based crop recommendation system**.
* Proposed a **cluster-based crop recommendation strategy**, offering multiple viable crops instead of a single output.
* Achieved **99.6% accuracy** using **Random Forest with K-fold cross-validation**, combined with **K-means clustering**.
* Presented at **ICISA 2024** and awarded **2nd Best Paper**.
* Extended version in progress, comparing **hard and soft clustering algorithms** with formal cluster validation metrics.

---

### A Python Library for Secret Image Sharing

**Tech:** Python, Galois, PIL, NumPy
**Repo:** [https://github.com/Abhiroop2004/Secret-Image-Sharing](https://github.com/Abhiroop2004/Secret-Image-Sharing)

* Developed a **cryptographically correct Python library** for:

  * (k, n) Visual Cryptography,
  * Lossless (k, n) and (t, k, n) Shamir’s Secret Sharing on images,
  * Regional Secret Image Sharing.
* Ensured **exact reconstruction** using **finite-field arithmetic (order 256)**.
* Ongoing work integrates **image segmentation and deep-learning-based inpainting** for region-aware secret sharing.
* Conducted under **Prof. Dr. Avishek Adhikary**, Presidency University.
