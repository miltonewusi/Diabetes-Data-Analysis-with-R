# Diabetes-Data-Analysis-with-R

## 🩺 Project Title:  
**Exploring Risk Factors Influencing Diabetes Outcomes Using Fasting Blood Glucose Data**

---

## 📘 Project Overview  
This project investigates the underlying risk factors associated with abnormal fasting blood glucose (FBG) levels, a key indicator of diabetes. Leveraging a structured dataset containing demographic, behavioral, and biometric variables, the analysis aims to uncover patterns and predictors of diabetes risk. The study aligns with public health priorities by identifying modifiable risk factors that can inform targeted interventions.

---

## 🧰 Tools & Technologies  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels  
- **Techniques**: Data wrangling, exploratory data analysis (EDA), logistic regression, data visualization

---

## 📊 Dataset Description  
The dataset comprises anonymized records of individuals with the following variables:
- **Demographics**: Age, Sex, Residence, Religion  
- **Behavioral Factors**: Alcohol Intake  
- **Biometric Indicators**: BMI, Obesity status  
- **Outcome Variable**: Fasting Blood Glucose (FBG)

A codebook was used to decode categorical variables and classify FBG levels into normal and abnormal categories based on clinical thresholds.

---

## 🔍 Analytical Approach  
1. **Data Cleaning & Transformation**  
   - Recoded categorical variables using the provided codebook  
   - Created derived variables: `FBG_Status` (binary outcome) and `BMI_Category`  

2. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of FBG, Age, and BMI  
   - Assessed relationships between FBG_Status and categorical predictors using bar plots and cross-tabulations  

3. **Statistical Modeling**  
   - Performed logistic regression to identify significant predictors of abnormal FBG  
   - Evaluated model performance using accuracy, precision, recall, and ROC-AUC  

4. **Visualization & Interpretation**  
   - Used boxplots, heatmaps, and bar charts to communicate findings  
   - Interpreted odds ratios to quantify the impact of each risk factor  

---

## 🎯 Key Findings  
- **Obesity and elevated BMI** were strongly associated with abnormal FBG levels  
- **Alcohol intake** and **urban residence** showed moderate predictive power  
- **Age** was a continuous predictor, with older individuals more likely to exhibit abnormal FBG  
- **Sex and religion** had limited predictive influence in this dataset  

---

## 🌍 Impact & Relevance  
This analysis contributes to evidence-based public health strategies by highlighting key risk factors for diabetes. The findings can support targeted awareness campaigns, lifestyle interventions, and resource allocation in both rural and urban settings.

---
