# 📊 Sales Effectiveness Analysis

This project explores the factors influencing sales performance in an organization using data-driven insights and machine learning models. The objective is to analyze employee attributes, uncover performance trends, and predict the effectiveness of sales personnel using classification algorithms.

---

## 🗂️ Project Structure

- `data/` - Contains raw and processed datasets
- `notebooks/` - Jupyter notebooks with EDA, preprocessing, and modeling
- `models/` - Saved machine learning models
- `outputs/` - Visualizations, reports, and evaluation results
- `README.md` - Project documentation

---

## 📌 Objectives

- Identify key factors affecting sales performance.
- Perform exploratory data analysis (EDA) to detect patterns and anomalies.
- Preprocess data to ensure quality and readiness for machine learning.
- Build and evaluate multiple classification models to predict sales effectiveness.

---

## 🔍 Exploratory Data Analysis (EDA)

- Analyzed distributions of features like experience, education, job level, and satisfaction metrics.
- Used correlation heatmaps, boxplots, and pair plots to study feature relationships.
- Highlighted key patterns such as:
  - Positive correlation between satisfaction levels and performance.
  - Performance improvements with more experience and better work-life balance.

---

## 🛠️ Data Preprocessing

- Missing value treatment using mean/mode imputation.
- Label Encoding for ordinal features (e.g., Satisfaction, Work-Life Balance).
- One-Hot Encoding for nominal categorical features.
- Feature scaling using Min-Max Scaler.
- Addressed class imbalance with SMOTE for fair model training.

---

## 🤖 Machine Learning Models

| Model               | Description                                       | Accuracy |
|--------------------|---------------------------------------------------|----------|
| **Support Vector Machine** | High training accuracy, tuned for generalization.      | 83.75%   |
| **Random Forest**         | Robust and interpretable, performed well on test data. | ~85%     |
| **MLP Classifier**        | Captured non-linear relationships with deep layers.    | ~84%     |

---

## 📈 Results

- Feature importance highlighted satisfaction, experience, and salary hike as top contributors.
- Tuned models provided good generalization on unseen data.
- Recommendations were derived to improve sales performance through targeted employee development.

---

## 🧰 Tools & Technologies

- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📚 References

- Data Dictionaries and Organizational Manuals
- IABAC Guidelines for Data Science Projects

---

## 🚀 Future Work

- Integrate dashboard for real-time performance monitoring.
- Apply advanced ensemble methods and deep learning.
- Expand dataset with customer feedback and external market data.

---

## 🧑‍💻 Author

**Deep [Your Full Name]**  
Feel free to connect via [LinkedIn](#) or email.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

