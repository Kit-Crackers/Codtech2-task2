

# Medical Cost Dataset Analysis  

## Objective  
The goal of this project is to analyze a medical cost dataset, uncover key patterns through Exploratory Data Analysis (EDA), and build a predictive machine learning model to estimate medical costs based on patient information.  

## Overview of Project 
![Screenshot 2025-01-07 211813](https://github.com/user-attachments/assets/b0470e73-6ef9-48c3-895e-29692375b562)
![Screenshot 2025-01-07 211829](https://github.com/user-attachments/assets/bec39419-54cb-40da-8de8-8d90b0741f1c)
![Screenshot 2025-01-07 211847](https://github.com/user-attachments/assets/3b95a7a8-7357-4f47-87d1-69fdbe209909)
![Screenshot 2025-01-07 211907](https://github.com/user-attachments/assets/a2b08210-1757-47d5-803e-9b9b116e9031)
![Screenshot 2025-01-07 211920](https://github.com/user-attachments/assets/08ed101e-d451-4772-9375-7756f8a09289)
![Screenshot 2025-01-07 211934](https://github.com/user-attachments/assets/8aaba022-af25-4408-9c4d-f569385a8282)

## Dataset  
The dataset contains patient data with features such as:  
- **Age**: Patient's age in years.  
- **BMI**: Body Mass Index, a measure of body fat based on height and weight.  
- **Children**: Number of dependents.  
- **Smoker**: Smoking status (Yes/No).  
- **Region**: Patient's residential area in the US.  
- **Charges**: Medical insurance costs (target variable).  

## Workflow  
1. **Data Preprocessing**:  
   - Handle missing or inconsistent values.  
   - Encode categorical variables (e.g., `smoker`, `region`).  
   - Scale numerical features (e.g., `age`, `BMI`).  

2. **EDA**:  
   - Visualize relationships between features and charges.  
   - Identify patterns (e.g., higher charges for smokers).  

3. **Feature Selection**:  
   - Evaluate feature importance for predicting charges.  

4. **Model Building**:  
   - Train regression models (e.g., Linear Regression, Random Forest).  
   - Evaluate models using metrics like R² and RMSE.  

5. **Result Analysis**:  
   - Report model performance and insights derived.  

## Libraries Used  
- **pandas**: Data manipulation and preprocessing.  
- **numpy**: Numerical computations.  
- **matplotlib & seaborn**: Data visualization.  
- **scikit-learn**: Machine learning model building and evaluation.  
