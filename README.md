# crop_prediction
# 🌾 Crop Yield Prediction using Machine Learning  

## 📌 Overview  
This project leverages **machine learning** to predict crop yield (production per unit area) based on various agricultural factors, such as **season, state, area, production, annual rainfall, fertilizer, and pesticide usage**. The model is trained on a dataset spanning **1997–2020**, covering multiple crops across different Indian states.  

## 🚀 Features  
✅ **Multi-Model Evaluation**: Uses multiple regression models (Linear Regression, Decision Tree, Random Forest, XGBoost, LightGBM, etc.)  
✅ **Data Preprocessing**: Handles missing values, encodes categorical features, and scales numerical values  
✅ **Performance Metrics**: Evaluates models using **MAE, RMSE, and R² Score**  
✅ **Flask API**: Deploys the trained model as a **web service**  
✅ **Interactive UI**: Provides a **user-friendly web interface** for predictions  
✅ **End-to-End Deployment**: Encodes categorical variables dynamically for real-time predictions  

## 📊 Dataset  
- **Source**: [Kaggle - Crop Yield in Indian States](https://www.kaggle.com/datasets/akshatgupta7/crop-yield-in-indian-states-dataset/data)  
- **Columns**: Crop, Year, Season, State, Area, Production, Rainfall, Fertilizer, Pesticide, Yield  

## 🛠️ Tech Stack  
🔹 **Python** (NumPy, Pandas, Scikit-learn, XGBoost, LightGBM)  
🔹 **Flask** (Backend API for model deployment)  
🔹 **HTML, JavaScript** (Frontend UI for input and results)  
🔹 **Joblib** (Model serialization for deployment)  

## 📂 Project Structure  
📁 Crop-Yield-Prediction │── 📂 data/ # Dataset and preprocessing scripts
│── 📂 models/ # Trained model & encoders (pkl files)
│── 📂 static/ # CSS & JS files for UI
│── 📂 templates/ # HTML files for Flask UI
│── 📝 app.py # Flask application
│── 📝 model_training.ipynb # Jupyter Notebook for training models
│── 📝 requirements.txt # Dependencies
│── 📝 README.md # Project Documentation
