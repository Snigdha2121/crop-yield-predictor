# Model Folder - Crop Yield Prediction

This folder contains the trained model and associated preprocessing files used for **Crop Yield Prediction**.

## 📂 Files in this Folder
```
📦 model
├── Crop_Yield_Prediction.ipynb  # Jupyter Notebook for model training
├── crop_yield_model.pkl         # Trained Gradient Boosting model
├── onehot_encoder.pkl           # OneHotEncoder used for categorical features
├── scaler.pkl                   # StandardScaler used for numerical features
```

## 📌 Description
- **Crop_Yield_Prediction.ipynb**: Contains the code for training the model using the Gradient Boosting Regressor.
- **crop_yield_model.pkl**: The trained model saved using `joblib`, which can be loaded for predictions.
- **onehot_encoder.pkl**: The fitted OneHotEncoder used for encoding categorical features during preprocessing.
- **scaler.pkl**: The fitted StandardScaler used for normalizing numerical features during preprocessing.

## 🔧 How to Use
1. Load the trained model in Python:
   ```python
   import joblib
   model = joblib.load("model/crop_yield_model.pkl")
   ```
2. Load the encoders for preprocessing input data:
   ```python
   encoder = joblib.load("model/onehot_encoder.pkl")
   scaler = joblib.load("model/scaler.pkl")
   ```
3. Use the loaded model to make predictions:
   ```python
   prediction = model.predict(preprocessed_input)
   print("Predicted Crop Yield:", prediction)
   ```

## 🚀 Future Work
- Implement version control for models.
- Save additional evaluation metrics for better insights.
- Deploy the model as an API for real-time predictions.

---
If you find this useful, give a ⭐ to this repo!

Happy coding! 🚀
