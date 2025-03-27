# 🌍 Global Financial Policy Analysis

This project analyzes and visualizes global financial policy responses to the COVID-19 pandemic. It combines machine learning classification models with advanced visualizations (Tableau and Plotly) to uncover patterns in how countries reacted financially to the global crisis.

---

## 🧠 Objectives

- Classify financial measures applied by countries.
- Understand which authorities and income levels influence policy decisions the most.
- Explore clusters of countries based on similar financial actions.
- Provide an interactive dashboard for exploratory data analysis.

---

## 📁 Project Structure


---

## 🔍 Exploratory Data Analysis (EDA)

- ✅ Distribution of income levels
- ✅ Frequency of policy types by authority
- ✅ Timeline of financial measures
- ✅ Country clustering using PCA & KMeans

---

## 🤖 Machine Learning Models

We trained and evaluated 3 classification models:
- **Random Forest**
- **Logistic Regression**
- **Gradient Boosting**

| Model               | Accuracy | Macro F1-score | Macro Recall |
|--------------------|----------|----------------|---------------|
| Random Forest       | 0.55     | 0.24           | 0.25          |
| Logistic Regression | 0.55     | 0.21           | 0.23          |
| Gradient Boosting   | 0.55     | 0.24           | 0.25          |

📌 *Random Forest showed the most balanced performance and was selected for feature importance analysis.*

---

## 📊 Tableau Dashboard

The Tableau dashboard provides a dynamic view of:
- Financial measures by income level
- Types of authority involved
- Timeline of policy applications
- Global distribution of financial actions

🔗 **[Download the Dashboard](./Global%20Political%20Dashboard.twb)**  
*(Open with Tableau Desktop)*

---

## 🛠️ Technologies Used

- Python (Pandas, Scikit-learn, Plotly, Seaborn)
- Tableau (for dashboard)
- Jupyter Notebook
- GitHub

---

## 📌 Key Findings

- Central Banks were the most active authority in policy implementations.
- High and upper-middle-income countries implemented the most measures.
- There's significant class imbalance in policy types that requires better balancing techniques.

---

## 📬 Contact

Created by [@juancos](https://github.com/juancos) — feel free to reach out for questions, collaborations or opportunities!

---

## 📜 License

This project is licensed under the MIT License.
