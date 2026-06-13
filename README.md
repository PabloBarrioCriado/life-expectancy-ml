# 🌍 Life Expectancy Prediction using Machine Learning

## 📊 Project Overview
This project explores global life expectancy using exploratory data analysis (EDA) and machine learning techniques to understand the key factors that influence population health outcomes and to build predictive models.

The main objective is to identify the most relevant predictors of life expectancy and evaluate different regression models in terms of predictive performance and generalization capability.

---

## 🎯 Objectives
- Perform exploratory data analysis on global health and socioeconomic data  
- Identify the most important factors influencing life expectancy  
- Compare multiple machine learning models  
- Evaluate models using standard regression metrics  
- Select and optimize the best-performing model  
- Assess real-world predictive reliability on unseen data  

---

## 📁 Dataset
The dataset includes country-level health, economic, and demographic indicators such as:
- HIV prevalence  
- Adult mortality  
- GDP
- Education indicators  
- Immunization coverage  
- Health expenditure  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- Jupyter Notebook  

---

## 🤖 Machine Learning Models
The following regression models were implemented and compared:

- Ridge Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Regression (SVR)  
- Random Forest Regressor  
- XGBoost Regressor  

---

## 📈 Model Evaluation & Selection
All models were evaluated using regression performance metrics such as R² and RMSE.

### Key findings:
- **Random Forest and XGBoost achieved the best and very similar predictive performance**
- Linear models (Ridge Regression) showed lower performance due to nonlinear relationships in the data  
- Distance-based models (KNN and SVR) underperformed compared to ensemble methods  
- The results confirm the presence of strong nonlinear patterns in the dataset  

---

## 🏆 Final Model: Random Forest Regressor

After comparing all models, **Random Forest was selected as the final model** due to its balance between performance and interpretability.

The model was further optimized through hyperparameter tuning, including tree depth and model complexity.

### Final results:
- Achieved an **R² close to 0.90**, indicating strong explanatory power  
- Hyperparameter tuning improved generalization and reduced prediction error  
- Robust performance across validation experiments  

### Real-world performance evaluation:
To assess practical applicability, an additional evaluation was performed on unseen data:

- The model predicts life expectancy within an error margin of **±2.5 years**  
- This level of accuracy was achieved in approximately **70% of unseen countries**  
- Results indicate strong generalization capability to new data  

---

## 📊 Key Insights
- HIV/AIDS and adult mortality are the strongest predictors of life expectancy   
- Nonlinear models significantly outperform linear approaches in this dataset  
- Ensemble methods provide the best overall predictive performance  

---

## 🚀 Future Improvements
- Further hyperparameter optimization using grid search or Bayesian optimization  
- Experiment with advanced boosting algorithms (LightGBM, CatBoost)  
- Feature engineering to capture additional nonlinear relationships  
- Model explainability using SHAP values for interpretability  

---

## 👤 Author
Pablo Barrio Criado
