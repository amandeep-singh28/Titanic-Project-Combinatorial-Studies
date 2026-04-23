# 🚢 Titanic Survival Prediction Project

## 📌 Overview
This project focuses on analyzing the Titanic dataset and building machine learning models to predict whether a passenger survived or not.

The workflow follows:
- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Building using Pipelines  

---

## 📂 Project Structure

TITANIC PROJECT - COMBINATORIAL STUDIES/

│  
├── Datasets/  
│   └── Titanic-Dataset.csv  

│  
├── 01_Data_Cleaning.ipynb  
├── 02_Data_Visualization.ipynb  
├── 03_Logistic_Regression.ipynb  
├── 04_Decision_Tree.ipynb  
├── 05_Random_Forest.ipynb  

│  
├── Data_Cleaning.csv  
├── README.md     

---

## 🧹 Data Cleaning
Performed in `01_Data_Cleaning.ipynb`

### Key Steps:
- Handled missing values:
  - Age → filled with median  
  - Embarked → filled with mode  
  - Cabin → dropped  

- Removed unnecessary columns:
  - PassengerId, Name, Ticket  

- Converted categorical data into numerical:
  - Sex → 0 (Male), 1 (Female)  
  - Embarked → encoded  

---

## 📊 Exploratory Data Analysis (EDA)
Performed in `02_EDA.ipynb`

### Visualizations:
- Survival count  
- Survival vs Gender  
- Survival vs Passenger Class  
- Age distribution  
- Fare distribution  
- Correlation heatmap  

### Key Insights:
- Females had higher survival rate  
- 1st class passengers survived more  
- Higher fare → higher survival chances  

---

## ⚙️ Feature Engineering
- FamilySize = SibSp + Parch  
- IsAlone feature  

---

## 🤖 Machine Learning Models

### Logistic Regression
- Uses StandardScaler  
- Baseline model  

### Decision Tree
- No scaling required  
- Captures non-linear patterns  

### Random Forest
- Ensemble method  
- Reduces overfitting  
- Best performance among models  

---

## 📈 Evaluation Metrics
- Accuracy Score  
- Precision  
- Recall  
- F1-score  

---

## 🧠 Key Learnings
- Data cleaning is crucial  
- Feature engineering improves results  
- Pipelines prevent data leakage  
- Model choice impacts performance  

---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Cross-validation  
- Feature importance analysis  
- Try advanced models  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📌 Conclusion
This project demonstrates a complete ML workflow from preprocessing to model evaluation.

---

## 👨‍💻 Author
Amandeep