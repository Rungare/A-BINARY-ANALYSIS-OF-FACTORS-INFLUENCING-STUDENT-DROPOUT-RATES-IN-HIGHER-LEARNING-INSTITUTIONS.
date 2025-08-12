# 🎓 Binary Analysis of Factors Influencing Student Dropout Rates in Higher Learning Institutions

## 📌 Overview
This project investigates the key factors influencing student dropout rates in higher learning institutions using **Logistic Regression**.  
The study explores **academic, socio-economic, and institutional factors**, aiming to provide **predictive insights** and **actionable strategies** to reduce dropout rates and improve retention.

---

## 🎯 Objectives
1. **Identify** statistically significant variables influencing student dropout.
2. **Measure** the strength of the relationship between these variables and dropout rates.
3. **Develop** a predictive model to forecast dropout likelihood.

---

## 🗂 Methodology
### 1️⃣ Data Collection
- **Sample:** 462 students
- **Method:** Structured questionnaire
- **Tools:** Python (Pandas, NumPy, Scikit-learn)

### 2️⃣ Statistical Analysis
- **Chi-Square Test:** Determine associations between categorical variables and dropout.
- **Cramer’s V Test:** Measure the strength of associations.

### 3️⃣ Predictive Modeling
- **Algorithm:** Logistic Regression
- **Feature Selection:** Recursive Feature Elimination (RFE)
- **Data Split:** 80% training, 20% testing
- **Evaluation Metrics:** Accuracy, Log Loss, ROC Curve, AUC

---

## 📊 Key Results
- **Significant Predictors:** Academic performance, seeking counseling, academic stress, health status, age.
- **Model Accuracy:** 75.3%
- **Log Loss:** 0.531 (low, indicating good probability calibration)
- **AUC:** 0.724 (moderate discrimination ability)
- Variables like **scholarship holder**, **family crisis**, **gender**, and **quality of teaching** had *p-values > 0.05* (less significant).

---

## 🧠 Insights
- Academic and mental health support significantly affect dropout likelihood.
- Age and health status play a role in retention.
- Certain factors traditionally assumed to matter (e.g., gender, scholarships) may be less predictive in this dataset.

---

## 📷 Visuals
<img width="901" height="554" alt="Screenshot 2023-12-04 143433" src="https://github.com/user-attachments/assets/28a7fcc0-1272-4e91-a8ee-d09d3f14dbd3" />
<img width="722" height="531" alt="Screenshot 2023-12-04 144117" src="https://github.com/user-attachments/assets/c010ae55-f500-4c8a-b4b3-6dcbe44cfc42" />



## 🛠 Tech Stack
- **Programming:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib
- **Statistical Tests:** Chi-Square, Cramer’s V
- **Model:** Logistic Regression

---

## 📝 Recommendations
- Offer **flexible payment plans** and **financial aid** for students with financial constraints.
- Foster **peer mentorship programs** and **inclusive support systems**.
- Implement **mental health and counseling services** for students under stress.
- Tailor academic resources to different **age groups** for targeted intervention.

---

## 📬 References
- Seidman, A. (2005). *College student retention: Formula for student success*. American Council on Education.  
- Rumberger, R. W. (2011). *Dropping out: Why students drop out of high school and what can be done about it*. Harvard University Press.  
- Tinto, V. (1993). *Leaving college: Rethinking the causes and cures of student attrition* (2nd ed.). University of Chicago Press.  
- Adelman, C. (2006). *The toolbox revisited: Paths to degree completion from high school through college*. US Department of Education.  

---
## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Rungare/A-BINARY-ANALYSIS-OF-FACTORS-INFLUENCING-STUDENT-DROPOUT-RATES-IN-HIGHER-LEARNING-INSTITUTIONS.git
   cd A-BINARY-ANALYSIS-OF-FACTORS-INFLUENCING-STUDENT-DROPOUT-RATES-IN-HIGHER-LEARNING-INSTITUTIONS
   ```
2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:

   ```bash
   python A-BINARY-ANALYSIS-OF-FACTORS-INFLUENCING-STUDENT-DROPOUT-RATES-IN-HIGHER-LEARNING-INSTITUTIONS.py
   ```

---

## 📬 Contact

For questions, feedback, or collaboration:

- **Name:** Evans Rung'are  
- **Email:** evansrungare@gmail.com  
- **LinkedIn:** [linkedin.com/in/evans-rungare](https://linkedin.com/in/evans-rungare)  
- **GitHub:** [github.com/Rungare](https://github.com/Rungare)  


