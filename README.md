# Mental-Health-Dynamics-Analysis  
*A data-driven analysis of mental health trends using machine learning and statistical methods on DASS scores.*

## Overview  
This project investigates the relationship between **personality traits, demographic factors, and mental health outcomes** using **statistical techniques and machine learning models**.  
The study aims to:  
- **Predict mental health conditions**  
- **Assess intervention effectiveness**  
- **Analyze Depression, Anxiety, and Stress Scales (DASS) scores** using **SPSS & Python**  

## Objectives  
- ✅ Evaluate the impact of **personality traits (TIPI)** on **DASS scores**.  
- ✅ Assess the effectiveness of **mental health interventions** using **pre/post-DASS score analysis**.  
- ✅ Identify **significant associations between demographic factors** (age, gender, education) and mental health outcomes.  
- ✅ Develop **predictive machine learning models** to classify mental health severity.  

## Key Statistics & Findings  
### Dataset  
- **39,775 responses** from the [Kaggle DASS dataset](https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses)  
- Responses categorized into **5 mental health severity levels**:  
  -  *Normal*  
  -  *Mild*  
  -  *Moderate*  
  -  *Severe*  
  -  *Extremely Severe*  

### Machine Learning Model Performance  
| Model | Accuracy | Precision | Recall |  
|--------|----------|-----------|--------|  
| **Logistic Regression** | **74%** | **78%** | **96%** |  
| Support Vector Machine (SVM) | 71% | 72% | 91% |  
| Random Forest | 71% | 73% | 89% |  

### Statistical Analysis (SPSS ANOVA Results)  
- **p-value < 0.001** → **Significant correlation** between **TIPI4 (Anxiety Trait) and DASS scores**.  
- **Age & Gender significantly influence mental health outcomes.**  
- **Intervention program showed a 15% reduction in average DASS scores.**  

## Technologies & Tools Used  
-  **Python** (Pandas, Scikit-learn, Matplotlib, Seaborn)  
-  **SPSS** (Statistical Hypothesis Testing)  
-  **CRISP-DM** (Data Science Workflow)  
-  **Machine Learning Models** (Logistic Regression, SVM, Random Forest)  
-  **GitHub for version control & collaboration**  

## Future Scope  
-  Implement **deep learning models (LSTMs)** for enhanced prediction accuracy.  
-  Expand dataset with **real-world intervention case studies**.  
-  Develop an **interactive dashboard** for real-time mental health monitoring.  

