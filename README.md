# Heart Disease Prediction using Machine Learning

This project predicts the likelihood of heart disease based on clinical features using machine learning models.  
The model is trained on the **Cleveland Heart Disease dataset** and applies **Principal Component Analysis (PCA)** for dimensionality reduction, followed by a **Random Forest Classifier** for prediction.

## 📌 Features
- **Dataset**: Cleveland Heart Disease dataset (`Heart_disease_cleveland_new(1).csv`)
- **Models Used**: Logistic Regression, KNN, Decision Tree, Random Forest, SVM, Naive Bayes
- **Best Model**: Random Forest (highest accuracy in tests)
- **PCA**: Reduces 14 original features to 13 principal components (based on feature importance)
- **Interactive Prediction**: `predict_from_input()` lets you enter patient data and get instant predictions

## 🧠 Dataset Information
**Columns**:
- `age` → Age of the patient (years)
- `sex` → 1 = Male, 0 = Female
- `cp` → Chest Pain Type (0=TA, 1=ATA, 2=NAP, 3=ASY)
- `trestbps` → Resting blood pressure (mm Hg)
- `chol` → Serum cholesterol (mg/dl)
- `fbs` → Fasting blood sugar > 120 mg/dl (1=Yes, 0=No)
- `restecg` → Resting ECG results (0=Normal, 1=ST, 2=LVH)
- `thalach` → Maximum heart rate achieved
- `exang` → Exercise induced angina (1=Yes, 0=No)
- `oldpeak` → ST depression
- `slope` → Slope of peak exercise ST segment (0=Up, 1=Flat, 2=Down)
- `ca` → Number of major vessels (0–3) colored by fluoroscopy
- `thal` → Thalassemia (0=Normal, 1=Fixed defect, 2=Reversible defect)
- `target` → 1 = Heart disease, 0 = No disease

## 🚀 Installation & Usage
### 1️⃣ Clone the repository
```bash
git clone https://github.com/cloudvity23/Heart-Disease-Prediction-Model.git
cd heart-disease-prediction
