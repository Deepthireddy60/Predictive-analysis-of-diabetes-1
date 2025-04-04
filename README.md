# Predictive Analysis of Diabetes Status using Machine Learning

This project utilizes various machine learning models to predict the diabetes status (Diabetic, Pre-Diabetic, or Non-Diabetic) of individuals using a dataset from Iraqi healthcare centers. The goal is to assist healthcare professionals in early detection and personalized treatment planning.

---

## 🧠 Project Overview

- **Goal**: Classify individuals based on health parameters into diabetic status categories.
- **Dataset**: Medical data from Al-Kindy Teaching Hospital, Iraq.
- **ML Models Used**: Random Forest, XGBoost, Logistic Regression, SVM, Decision Trees, and more.
- **Best Models**: Random Forest & XGBoost (99% accuracy).
- **Tech Stack**: Python, Pandas, scikit-learn, XGBoost, Matplotlib, Seaborn

---

## 📊 Features Used

- Age  
- Gender  
- BMI  
- Cholesterol  
- HbA1c  
- Urea  
- Triglycerides  
- VLDL  
- (Dropped: HDL, LDL, Cr due to low significance)

---

## 🔍 Methodology

1. **Data Collection**
2. **Preprocessing** (outlier removal, missing values)
3. **Exploratory Data Analysis**
4. **Feature Selection**
5. **Model Development** using 12 classifiers
6. **Performance Evaluation** via Accuracy, F1-Score, ROC Curves
7. **Class Imbalance Handling** via SMOTE

---

## 📈 Results

- **Random Forest** & **XGBoost** achieved 99% classification accuracy.
- **Class 0 (Non-Diabetic)** had the best AUC across all models.
- Features like **HbA1c**, **BMI**, and **Age** had the highest statistical significance.

---

## 👩‍💻 Team Members

| Name                | Background               | Contributions                              |
|---------------------|--------------------------|---------------------------------------------|
| Pavithra Kadri      | MBBS                     | Coordination, Data Cleaning, Presentation   |
| Deepthi Mallepally  | BDS                      | Statistical Testing, Data Transformation    |
| Deva Harsha Gubbala | BSc Microbiology         | EDA, Data Visualization                     |
| Amulya Ragula       | BSc Agriculture          | Feature Engineering, Statistical Testing    |
| Sharmila Shree V    | BDS                      | Model Building & Evaluation                 |

---

## 🧪 Challenges

- **Imbalanced dataset** – handled with SMOTE
- **Non-normal distribution** – applied non-parametric tests
- **Unique dataset** – limited external references

---

## 📂 How to Run

1. Clone this repo:
    ```bash
    git clone https://github.com/your-username/predictive-analysis-of-diabetes.git
    ```
2. Install requirements:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the main script or Jupyter notebook.

---

## 📚 References

- Rashid, A. (2020). [Diabetes Dataset](https://doi.org/10.17632/wj9rwkp9c2.1)
- American Diabetes Association (2021)
- More in the appendix of the project report.

---

## 📌 Note

This study is based on region-specific data and findings may not generalize to global populations. Further testing with diverse datasets is encouraged.

