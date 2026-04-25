# 🎮 Comprehensive Gamer Preference Analysis

This repository contains the complete data analytics workflow for a Major Project evaluating the habits, motivations, and impacts of video gaming on individuals. It explores how gaming behaviors (hours played, frequency, time of day) influence physiological and psychological outcomes such as sleep cycles, stress levels, perceived addiction, and academic performance.

## 📂 Repository Contents

* **`project.ipynb`**: The core Jupyter Notebook containing the entire Python data pipeline. Includes data cleaning, Exploratory Data Analysis (EDA) with advanced visualizations (heatmaps, violin plots), and machine learning model training (Logistic Regression, Linear Regression, and an optimized Random Forest).
* **`gamer_dashboard.html`**: A fully interactive, standalone data visualization dashboard built to explore gamer demographics, addiction levels, and sleep impact. Open this file in any web browser to interact with the charts.
* **`Report.pdf`**: The final academic report detailing the project objective, methodology, model performance metrics, and conclusive insights.

## 🛠️ Tech Stack & Methodologies
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn, Plotly
* **Machine Learning:** Scikit-Learn (Classification & Regression)
* **Advanced Techniques:** Imbalanced data handling (SMOTE), Feature Engineering (One-Hot Encoding), Hyperparameter Tuning (GridSearchCV)

## 💡 Key Findings
* **Academic Impact:** The majority of casual gamers experience no negative academic impact; however, negative impacts spike dramatically for those reporting high subjective addiction scores.
* **The Tipping Point:** Gaming beyond 4 hours a day results in a severe deterioration of self-reported sleep quality.
* **Predictive Modeling:** An optimized Random Forest Classifier (68.75% accuracy) identified that *Hours Played*, *Sleep Impact*, and contextual habits like *Late Night Gaming* and *Gaming for Stress Relief* are the strongest predictors of highly addicted players.

## 🚀 How to Use
1. Clone the repository to your local machine.
2. Open `gamer_dashboard.html` in Chrome, Safari, or Edge to view the interactive visualizations.
3. To run the code, ensure you have Python installed along with the required libraries (`pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn plotly`), and open `project.ipynb` in Jupyter or VS Code.