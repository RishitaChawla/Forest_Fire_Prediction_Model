
# 🔥 Leveraging Machine Learning for Forest Fire Prediction
Built a machine learning classifier model to predict “Fire” vs “No Fire” for a region using weather conditions and Fire Weather Index (FWI) features as input.

## 🚀 How to Run
1. Open the MLModel.ipynb in Google Collab + install & upload Algerian_forest_fires_dataset.csv in content file
2. Run the notebook in order:
   - `preprocess` → `train` → `evaluate`

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
- 📈 Fire Weather Indices(FWI): FFMC, DMC, DC, ISI, BUI, FWI


## 🔭 Next Improvements
- Try stronger models (Random Forest, XGBoost, Neural Nets)  
- Add richer features (soil moisture, vegetation, drought indices)  
- Integrate real-time weather/satellite feeds 

<p align="center"><em>⭐ Please feel free to explore my other projects on Github ⭐</em></p>
