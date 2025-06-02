# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Overview
This project aims to predict **heart disease** using supervised machine learning models based on clinical data. We analyze data patterns, perform feature selection, compare multiple classifiers, and tune hyperparameters to maximize prediction accuracy.

**Dataset Used:** [Heart Disease Dataset - Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
**Team:** Kelompok 8 – Final Project for Kecerdasan Artifisial Lanjut (TIF-A)

---

## ⚙️ Features
✅ **Exploratory Data Analysis (EDA)**  
✅ **Gender- and Chest Pain-based Disease Insights**  
✅ **Correlation Analysis & Feature Importance (Random Forest)**  
✅ **Model Training & Comparison**  
✅ **Hyperparameter Tuning (KNN & Random Forest)**  
✅ **Evaluation with Confusion Matrix & ROC-AUC Curve**  
✅ **Feature Importance Visualization**  

---

## 🏗️ Models Used
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)** 🔥 *(Best generalization after tuning)*
- **Random Forest** *(Highest raw accuracy, but prone to overfitting)*

---

## 📂 Project Structure
```

/HeartDiseasePrediction-Kelompok8
│── Kelompok8\_ProjectAkhirKAL.ipynb        # Main Jupyter Notebook (Modeling, EDA, Visualization)
│── Kelompok 8\_Heart Disease Prediction using Machine Learning.pdf  # Presentation Slide Deck
│── Kelompok 8\_Project Akhir KAL.pdf       # Final Paper/Journal Format
│── heart.csv                              # Dataset file (source: Kaggle)
│── README.md                              # Project Documentation (this file)

````

---

## 📈 Results & Findings
🔹 **Correlation analysis** showed that the most influential features are:
- `cp` (chest pain type)  
- `thalach` (maximum heart rate)  
- `slope` (ST depression slope)  
- `ca` (number of major vessels)

🔹 **Random Forest** initially achieved **100% accuracy**, but further evaluation indicated possible overfitting.

🔹 **K-Nearest Neighbors (KNN)** with hyperparameter tuning reached **98.54% accuracy**, offering better balance between performance and generalization.

🔹 Feature importance analysis confirmed that **chest pain type (`cp`)**, **thalassemia (`thal`)**, and **vessel count (`ca`)** were key drivers in prediction.

---

## 🚀 How to Run
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/nadhif-royal/HeartDiseasePrediction-Kelompok8.git
cd HeartDiseasePrediction-Kelompok8
````

### 2️⃣ Install Required Packages (Optional)

```bash
pip install pandas scikit-learn matplotlib seaborn numpy
```

### 3️⃣ Run the Jupyter Notebook

You can either:

* Run it locally via:

```bash
jupyter notebook
```

* Or open `Kelompok8_ProjectAkhirKAL.ipynb` in **Google Colab** for cloud-based execution.

---

## 🧠 Model Evaluation Metrics

We used various classification metrics:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**
* **ROC Curve & AUC Score**
* **Feature Importance Plot**

---

## 👨‍🏫 Contributors

**Fikri Adyatma** – 235150201111015

**Nadhif Rif’at Rasendriya** – 235150201111074

**Reyno Benedict** – 235150207111048

---

## 📜 License

This project is for educational and academic purposes only.
Please credit the authors when using this project for learning or demonstrations.

---

💡 *Feedback, suggestions, and collaborations are always welcome!*

```


