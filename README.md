# Crop Yield Prediction using Gradient Boosting

This repository contains a **Crop Yield Prediction Model** implemented using the **Gradient Boosting Algorithm**, a supervised learning technique for regression.

## 📌 Project Overview
This model predicts crop yield (in tons per hectare) based on various environmental and agricultural factors, using data preprocessing and machine learning techniques.

## 📂 Repository Structure
```
📦 crop-yield-prediction
├── 📂 model
│   ├── crop_yield_model.pkl
│   ├── onehot_encoder.pkl
│   ├── scaler.pkl
├── 📂 dataset
│   ├── dataset.csv
├── 📜 README.md
```

## 📜 Dataset
The dataset includes the following features:
- **Categorical Features:** Crop, Sowing Month, Harvest Month, State, District
- **Numerical Features:** Rainfall, Mean Temperature, Humidity, Soil pH, Nitrogen, Phosphorus, Potassium, Market Price, Cultivation Area, Production Volume
- **Target Variable:** Crop Yield (tons/ha)

## 📌 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/crop-yield-prediction.git
   cd crop-yield-prediction
   ```
2. Install necessary dependencies (if not already installed):
   ```bash
   pip install pandas numpy scikit-learn joblib
   ```
3. Open the Jupyter Notebook and run the cells to train the model:
   ```bash
   jupyter notebook Crop_Yield_Prediction.ipynb
   ```
4. The model will be trained using the dataset available in the `dataset` folder.
5. The trained model will be saved within the notebook execution.

## 📊 Model Performance
- **Mean Absolute Error:** `0.0176`
- **R² Score:** `0.9997`

## 🚀 Future Improvements
- Hyperparameter tuning for better performance
- Experimenting with other models (Random Forest, Neural Networks)
- Deployment as a web API for real-time predictions

---

If you find this useful, give a ⭐ to this repo!

Happy coding! 🚀
