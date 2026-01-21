# AI & ML Internship - Task 4: Feature Encoding & Scaling

This project demonstrates essential Data Preprocessing and Feature Engineering techniques using the **Adult Income Dataset**.

## 🎯 Objectives
- Identify and separate numerical and categorical features.
- Apply **Label Encoding** for binary and ordinal categories.
- Apply **One-Hot Encoding** for nominal categorical variables.
- Implement **Standard Scaling** to normalize numerical data.
- Analyze the impact of these transformations on Machine Learning model readiness.

## 📂 Files in this Repository
- `Adult_Income_Feature_Engineering.ipynb`: The complete Google Colab notebook.
- `adult.csv`: The original raw dataset.
- `processed_adult_income.csv`: The final, encoded, and scaled dataset ready for ML.

## 🛠️ Key Transformations
1. **Target Encoding:** Converted `income` to numerical values (0 for <=50K, 1 for >50K).
2. **Nominal Handling:** Expanded `occupation`, `workclass`, and `race` using One-Hot encoding to avoid mathematical bias.
3. **Scaling:** Used `StandardScaler` on features like `age`, `capital-gain`, and `hours-per-week`.

## 💡 Why Scaling Matters
Scaling is vital for algorithms that rely on distance metrics (like KNN) or optimization (like Logistic Regression). Without scaling, a feature with a larger numerical range would dominate the model's learning process, leading to inaccurate predictions.

---
**Author:** [gummadidala ashish kumar]
**Task:** Task 4 - Feature Encoding & Scaling
