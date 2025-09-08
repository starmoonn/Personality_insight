# Personality Classification Project (Extrovert vs. Introvert)

##  Overview
This project explores the **Extrovert vs. Introvert Personality Traits Dataset**, a collection of behavioral and social data.  
The goal is to perform **data analysis & machine learning** to uncover behavioral differences between personality types and build a model that can classify individuals with high accuracy.  

This project is designed as a **Data Analyst portfolio project**, covering the full workflow:
- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Data visualization for insights  
- Building and evaluating machine learning models  
- Communicating results with clear visualizations and reports  

---

##  Dataset
- **Size**: 2,900 rows × 8 columns  
- **Features**:
  - `Time_spent_Alone`: Hours spent alone daily (0–11)  
  - `Stage_fear`: Stage fright (Yes/No)  
  - `Social_event_attendance`: Frequency of social events (0–10)  
  - `Going_outside`: Frequency of going outside (0–7)  
  - `Drained_after_socializing`: Feeling drained after socializing (Yes/No)  
  - `Friends_circle_size`: Number of close friends (0–15)  
  - `Post_frequency`: Social media post frequency (0–10)  
  - `Personality`: Target variable (Extrovert/Introvert)  

---

##  Methodology
1. **Data Cleaning & Preprocessing**
   - Handled missing values (median for numeric, mode for categorical)  
   - Encoded binary variables (Yes/No → 1/0)  
   - Encoded target (`Extrovert` = 1, `Introvert` = 0)  

2. **Exploratory Data Analysis (EDA)**
   - Visualized personality distribution  
   - Compared average behaviors (e.g., time spent alone, social events, posting frequency)  
   - Histograms with mean & median lines for better interpretability  

3. **Modeling**
   - Train/Test split (80/20, stratified)  
   - Models: Logistic Regression & Random Forest  
   - Evaluated using Accuracy, Precision, Recall, F1-score, and ROC-AUC  

4. **Explainability**
   - Feature importance (Random Forest) or coefficients (Logistic Regression)  
   - Identified strongest predictors of personality type  

---

##  Results
- Both models achieved **~91% accuracy** on test data.  
- **Top predictors** of personality:  
  - Social event attendance  
  - Time spent alone  
  - Post frequency  
  - Friends circle size  

- Visualizations:
  - Personality class distribution  
  - Behavior comparison barplots  
  - Improved histograms with mean/median lines  
  - Confusion matrix  
  - Feature importance chart  

---

##  Key Insights
- **Extroverts** attend more social events, have larger friend circles, and post more frequently.  
- **Introverts** spend significantly more time alone and feel drained after socializing.  
- These behavioral indicators are strong predictors for personality classification.  

---

##  Skills Demonstrated
- Data Cleaning & Preprocessing (missing values, encoding, normalization)  
- Exploratory Data Analysis (EDA) & Visualization (Matplotlib)  
- Statistical reasoning (mean/median comparison, distributions)  
- Machine Learning modeling (Logistic Regression, Random Forest)  
- Model evaluation with multiple metrics (Accuracy, Precision, Recall, F1, ROC-AUC)  
- Communicating insights through visualizations & reports  

---
