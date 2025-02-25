# Dataset Folder - Crop Yield Prediction

This folder contains the dataset used for training the **Crop Yield Prediction** model.

## 📂 Files in this Folder
```
📦 dataset
├── dataset.csv  # Dataset containing crop yield and related features
```

## 📜 Dataset Description
The dataset includes various agricultural and environmental factors used to predict crop yield.

### Features in the Dataset:
- **Categorical Features:**
  - Crop
  - Sowing Month
  - Harvest Month
  - State
- **Numerical Features:**
  - Rainfall (mm)
  - Mean Temperature (°C)
  - Humidity (%)
  - Soil pH
  - Nitrogen (kg/ha)
  - Phosphorus (kg/ha)
  - Potassium (kg/ha)
  - Market Price (₹/kg)
  - Cultivation Area (ha)
  - Production Volume (tons)
- **Target Variable:**
  - Crop Yield (tons/ha)

## 🔧 How to Use the Dataset
1. Load the dataset in Python:
   ```python
   import pandas as pd
   df = pd.read_csv("dataset/dataset.csv")
   print(df.head())
   ```
2. Perform exploratory data analysis (EDA) to understand data distribution and patterns.
3. Preprocess the dataset before training the model (handling missing values, encoding categorical variables, scaling numerical features, etc.).

## 🚀 Future Work
- Update the dataset with more recent agricultural data.
- Add additional features to improve model accuracy.
- Create multiple dataset versions for experimentation.

---
If you find this useful, give a ⭐ to this repo!

Happy coding! 🚀
