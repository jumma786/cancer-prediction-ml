# 🧠 Cancer Prediction using Machine Learning

🚀 End-to-end Machine Learning project to predict whether a tumour is **malignant (M)** or **benign (B)** using medical diagnostic data.

---

## 📌 Project Overview

Early detection of cancer is critical for effective treatment.
This project builds a machine learning model to classify tumours based on medical features such as radius, texture, and area.

The project covers the full data science workflow:

* Data cleaning
* Exploratory Data Analysis (EDA)
* Feature analysis
* Model building
* Evaluation

---

## 📊 Dataset Information

* Dataset: Breast Cancer Dataset
* Number of records: ~569
* Features: 30 numerical features (radius, texture, perimeter, area, etc.)
* Target Variable:

  * `diagnosis`

    * M → Malignant (1)
    * B → Benign (0)

---

## 🧹 Data Preprocessing

* Removed unnecessary columns (e.g., `id`)
* Standardised column names (lowercase, removed spaces)
* Converted diagnosis into numeric values
* Checked for missing values (none found)

---

## 🔍 Exploratory Data Analysis (EDA)

* Visualised distribution of diagnosis (Benign vs Malignant)
* Analysed feature relationships using correlation heatmap
* Identified important predictive features

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🤖 Machine Learning Model

* Logistic Regression

### Workflow:

1. Train-test split (80/20)
2. Model training
3. Prediction
4. Evaluation

---

## 📈 Model Performance

* Accuracy: **92.1%**

✅ The model performs well in distinguishing between malignant and benign tumours.

---

## 💡 Key Insights

* Benign cases are more common than malignant cases
* Features like radius, perimeter, and area strongly influence prediction
* Clean data significantly improves model performance

---

## ▶️ How to Run the Project

```bash
git clone https://github.com/your-username/cancer-prediction-ml.git
cd cancer-prediction-ml
pip install -r requirements.txt
jupyter notebook
```

---

## 📁 Project Structure

cancer-prediction-ml/
│── data-cancer.csv
│── Cancer_prediction.ipynb
│── README.md
│── requirements.txt

---

## 🚀 Future Improvements

* Improve accuracy using Random Forest / XGBoost
* Hyperparameter tuning
* Add Confusion Matrix & ROC Curve
* Deploy using Streamlit

---

## 📬 Contact

* GitHub: https://github.com/your-username
* LinkedIn: https://linkedin.com/in/your-profile
