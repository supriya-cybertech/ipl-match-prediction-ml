# 🏏 IPL Match Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-CB3B27?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-437CCF?style=for-the-badge&logo=seaborn&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-00445E?style=for-the-badge&logo=xgboost&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

Predicting IPL match outcomes using **Machine Learning models** based on historical match data, player statistics, and team performance. This project provides **data-driven insights** for cricket enthusiasts, analysts, and sports researchers.

---

## 📂 Dataset

The dataset is stored in the ipl_colab.csv folder.  

**Note:** The dataset is large and cannot be previewed directly on GitHub. Click **"View raw"** to download it.

### Files Included:
- ipl_matches.csv → Match-level details (teams, venue, toss, result, winner, etc.)  
- ipl_deliveries.csv → Ball-by-ball details (batsman, bowler, runs, wickets, player performance)  

> These datasets are preprocessed and used for feature engineering, model training, and evaluation.

---

## ⚙️ Tech Stack
- **Programming Language:** Python 3.x  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning Models:** Scikit-learn (Logistic Regression, Random Forest, XGBoost, etc.)  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 🏗️ Project Flowchart
```mermaid
flowchart TD
    A([📂 Raw IPL Dataset]) --> B([🧹 Data Cleaning & Preprocessing])
    B --> C([⚒️ Feature Engineering])
    C --> D([📊 Exploratory Data Analysis])
    D --> E([🤖 Model Training & Selection])
    E --> F([📈 Model Evaluation & Metrics])
    F --> G([🏏 Match Outcome Prediction])

    classDef input fill:#f1f5f9,stroke:#334155,stroke-width:2px,color:#000,font-weight:bold
    classDef process fill:#e0f2fe,stroke:#0369a1,stroke-width:2px,color:#000,font-weight:bold
    classDef analysis fill:#fde68a,stroke:#b45309,stroke-width:2px,color:#000,font-weight:bold
    classDef model fill:#dcfce7,stroke:#166534,stroke-width:2px,color:#000,font-weight:bold
    classDef output fill:#bbf7d0,stroke:#065f46,stroke-width:3px,color:#000,font-weight:bold

    class A input
    class B,C process
    class D analysis
    class E model
    class F analysis
    class G output

