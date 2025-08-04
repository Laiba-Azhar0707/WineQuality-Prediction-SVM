# 🍷 Wine Quality Prediction using Support Vector Machine (SVM)

This project uses Support Vector Classifier (SVC) to predict whether red wine is "good" or "not good" based on its physicochemical properties.

## 📁 Dataset
- [Wine Quality (Red)](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- 11 input features (e.g., acidity, alcohol, pH)
- Binary classification: Quality >= 7 → Good (1), else Not Good (0)

## 💻 Tools & Libraries
- Python, Pandas, scikit-learn
- SVM with RBF kernel
- Data preprocessing & StandardScaler

## 🧠 Model Performance
- Accuracy: ~84%
- ROC AUC: 0.88
- High recall on "Good" wines, some precision tradeoff

## 📊 Future Improvements
- Use SMOTE or resampling to balance dataset
- Try ensemble models like RandomForest or XGBoost
- Hyperparameter tuning (C, gamma)

## 📂 How to Run
1. Clone the repo
2. Install dependencies (`pip install -r requirements.txt`)
3. Run the notebook
