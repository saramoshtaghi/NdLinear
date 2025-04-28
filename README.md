# ❤️ Heart Disease Prediction with Random Forest

This project uses the UCI Heart Disease dataset to predict the likelihood of heart disease in a patient using **Random Forest Classification**. It’s a great example of applying machine learning to a real-world healthcare problem, providing both explainability (feature importance) and strong performance.

---

## 📊 Dataset

- **Source**: UCI Heart Disease (Cleveland dataset)
- **Features** include:
  - `age`: Age of the patient
  - `sex`: Gender (0 = female, 1 = male)
  - `cp`: Chest pain type
  - `trestbps`: Resting blood pressure
  - `chol`: Serum cholesterol (mg/dl)
  - `fbs`: Fasting blood sugar > 120 mg/dl
  - `restecg`: Resting electrocardiographic results
  - `thalach`: Maximum heart rate achieved
  - `exang`: Exercise-induced angina
  - `oldpeak`: ST depression induced by exercise
  - `slope`, `ca`, `thal`: Additional ECG/thalassemia indicators
- **Target**:  
  - `condition`: 0 = No Heart Disease, 1 = Heart Disease

---

## 🔍 ML Model

- Algorithm: **Random Forest Classifier**
- Parameters:
  - `n_estimators=100` (100 decision trees)
  - `random_state=42` (ensures reproducibility)
- Train/test split: 80% training, 20% testing
- Feature importance is visualized to interpret model decisions

---

## 📈 Performance

- **Accuracy**: ~85–90% (varies slightly run to run)
- **Evaluation Metrics**:
  - Confusion Matrix (Visualized with seaborn)
  - Classification Report (Precision, Recall, F1-score)
  - Feature Importance Plot

---

## 🚀 To Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/saramoshtaghi/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook**  
   ```bash
   jupyter notebook heart_disease_rf.ipynb
   ```

---

## 📊 Visuals

- 📌 Confusion matrix to show classification results
- 📌 Bar plot of feature importances
- 📌 Tree visualization (1 sample tree from the Random Forest)

---

## 🧠 Insights

- Random Forest offers a strong baseline model for binary classification
- Feature importance helps identify key risk factors like `cp`, `thalach`, and `oldpeak`
- Useful for early-stage heart disease screening and educational use cases

---

## 📁 Folder Structure

```
📦heart-disease-prediction
 ┣ 📊 heart_cleveland_upload.csv     # Dataset file
 ┣ 📓 heart_disease_rf.ipynb         # Jupyter notebook with full pipeline
 ┣ 📜 README.md                      # Project overview
 ┣ 📦 requirements.txt               # Python dependencies
```

---

## 👩‍💻 Author

**Sara Moshtaghi**  
PhD Candidate in Computer Science  
Specializing in NLP, Recommender Systems, and Machine Learning  
🔗 [GitHub](https://github.com/saramoshtaghi) | ✉️ moshtasa@mail.uc.edu

---

## 🤝 Contributing

If you'd like to contribute by improving the model, adding visualizations, or testing with other algorithms — feel free to open an issue or a pull request!

---

## 📄 License

This project is licensed under the MIT License.

---
