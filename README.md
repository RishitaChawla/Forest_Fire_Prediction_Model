# 🔥 Leveraging Machine Learning for Forest Fire Prediction
Built a machine learning classifier model to predict “Fire” vs “No Fire” for a region using weather conditions and Fire Weather Index (FWI) features as input.

## 🎯 Impact
Enables early wildfire risk detection of regions, supporting faster response times and smarter deployment of firefighting resources.

## 🧠 What I Did
- 🧹 **Data cleaning & preprocessing**: standardized headers, handled missing data, simplified labels, fixed datatypes, scaled features, train/test split (75/25)
- 📊 **Exploration & feature analysis**: visualization + feature selection.
- 🤖 **Model training**: KNN, Gaussian Naive Bayes, Logistic Regression. 
- ✅ **Evaluation**: confusion matrix + accuracy-based comparison across models. 
- 🏆 **Best model (in this scope)**: Logistic Regression (fast + interpretable + strongest test performance).  

## 📌 Dataset Features
- 🌡️ Weather: temperature, humidity, wind speed, rainfall  
- 📈 FWI indices: FFMC, DMC, DC, ISI, BUI, FWI

Here are the FWI (Fire Weather Index) system indices in short, clear terms:

FFMC (Fine Fuel Moisture Code) 🔥
How dry the surface litter is (leaves, small twigs). Higher = easier to ignite.

DMC (Duff Moisture Code) 🍂
Dryness of the shallow organic layer under the surface. Higher = fires spread/smolder more.

DC (Drought Code) 🌵
Long-term dryness of deep, compact organic matter. Higher = drought conditions, harder-to-control fires.

ISI (Initial Spread Index) 🌬️
How fast a fire can spread at the start, mainly driven by wind + surface fuel dryness.

BUI (Build Up Index) 🪵
How much fuel is available to burn (combines DMC + DC). Higher = more intense potential fire.

FWI (Fire Weather Index) 📈
Overall fire intensity risk (a combined final score). Higher = more severe fire potential.

## 🚀 How to Run
1. Create environment + install Algerian_forest_fires_dataset.csv
2. Run the notebook/script in order:
   - `preprocess` → `train` → `evaluate`

> (Add your real filenames here, like `fire_forecasting.ipynb` or `src/train.py`.)

## 🔭 Next Improvements
- Try stronger models (Random Forest, XGBoost, Neural Nets)  
- Add richer features (soil moisture, vegetation, drought indices)  
- Integrate real-time weather/satellite feeds :contentReference[oaicite:9]{index=9}

<p align="center"><em>⭐ Please feel free to explore all my projects below which have detailed explanations ⭐</em></p>
