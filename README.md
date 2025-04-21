# Titanic Survival Prediction 🚢

This project builds a machine learning model to predict whether a passenger survived the Titanic disaster.

## 📂 Dataset
The dataset contains passenger information such as:
- Age, Gender, Ticket Class
- Fare, Cabin Info, Embarked Location
- Siblings/Spouses and Parents/Children aboard

## 🧹 Preprocessing
- Dropped irrelevant columns: `Name`, `Ticket`, `Cabin`, `PassengerId`
- Handled missing values with median imputation
- Encoded categorical features using one-hot encoding
- Scaled numerical features using StandardScaler

## 🤖 Model
- **Model Used**: Random Forest Classifier
- **Pipeline**: Combined preprocessing and model into one clean pipeline
- **Evaluation Metrics**:
  - Accuracy: 100%
  - Precision, Recall, F1-score: 100% on both classes (note: small dataset may overfit)

## 📊 Results
The model performed perfectly on the test set, but caution is advised as it may be overfitting due to the dataset size.

## 🚀 How to Run
1. Clone the repo
2. Place the `tested.csv` file in the project directory
3. Open and run the `Titanic_Survival_Prediction.ipynb` notebook

## 📁 Files
- `Titanic_Survival_Prediction.ipynb`: Jupyter notebook with all steps
- `tested.csv`: Input dataset (not included here, you must upload it separately)

---

Made with ❤️ for machine learning exploration.
