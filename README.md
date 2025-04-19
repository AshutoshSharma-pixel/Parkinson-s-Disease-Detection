# 🧠 Parkinson's Disease Detection Using Machine Learning

This project uses machine learning techniques to detect Parkinson's Disease based on a range of biomedical voice measurements. It applies a Support Vector Machine (SVM) model to classify whether a person is affected by the disease.

---

## 📁 Dataset

The dataset used in this project was obtained from the **UCI Machine Learning Repository**. It consists of **195 voice recordings** from individuals, each with **22 voice-related features** extracted using signal processing techniques.

- **Target column**: `status` (1 = Parkinson’s Disease, 0 = Healthy)

---

## 📊 Features

Key features used include:
- **MDVP:Fo(Hz)** – Average vocal fundamental frequency
- **Jitter, Shimmer** – Measures of variation in frequency and amplitude
- **NHR, HNR** – Noise-to-harmonics and harmonics-to-noise ratios
- **DFA, RPDE, PPE** – Nonlinear dynamic complexity measures

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Google Colab

---

## 🧠 Model

The main model used in this project is:

- **Support Vector Machine (SVM) with Linear Kernel**
  - Efficient for linearly separable data
  - Scaled features using `StandardScaler`

---

## 🔬 Steps Performed

1. Data loading and exploration
2. Checking for missing values
3. Splitting data into training and test sets
4. Feature scaling using `StandardScaler`
5. Training the model using `SVC(kernel='linear')`
6. Evaluating model performance using `accuracy_score`

---

## ✅ Results

The SVM model achieved **high accuracy** on the test set, demonstrating its effectiveness in classifying Parkinson’s cases from voice data.

---

## 📈 Future Work

- Try other classification models (Logistic Regression, Random Forest)
- Perform hyperparameter tuning (GridSearchCV)
- Implement cross-validation
- Add a front-end interface for real-world testing

---

## 🙌 Acknowledgements

- Dataset source: [UCI Parkinson’s Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- Project inspired by health-focused ML applications

---

## 📌 Author

**Ashutosh Sharma**  
[LinkedIn](https://www.linkedin.com/in/ashutosh-sharma-79557728a/) • [GitHub](https://github.com/AshutoshSharma-pixel)

