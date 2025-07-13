# 📱 Mobile Price Prediction Using Classification
## 🎯 Objective
The goal of this project is to build a machine learning classification model that predicts the **price range (0 to 3)** of a mobile phone based on its specifications such as battery power, RAM, storage, camera megapixels, etc.

This project demonstrates **feature engineering, classification algorithms, and model evaluation** techniques.

---
## 📂 Dataset Information

The dataset contains several features of mobile phones:

- Battery Power
- RAM
- Internal Memory
- Primary/Secondary Camera
- Bluetooth, 4G, WiFi, Touchscreen, etc.
- **Target Variable**: `price_range` (0 = Low Cost, 3 = Very High Cost)

---
## ⚙️ Features Implemented

- ✅ Data loading and exploration
- ✅ Class distribution analysis
- ✅ Data preprocessing and feature scaling
- ✅ Model training using:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- ✅ Evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- ✅ (Bonus) Feature importance and selection (optional)

---
### 🛠️ Install Dependencies

```bash
# Clone the repository
git clone https://github.com/your-username/mobile-price-prediction.git
cd mobile-price-prediction

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install required packages
pip install -r requirements.txt
