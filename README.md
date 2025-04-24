# 🌾 AgriSmart - Crop Recommendation System

This machine learning project recommends the most suitable crop to grow based on key environmental conditions such as soil nutrients and climate factors. It uses various classification algorithms and evaluates their performance to determine the best model for accurate predictions.

## 📊 Dataset

The dataset `Crop_recommendation.csv` contains 2200 samples and 8 features:

- `N`, `P`, `K`: Soil nutrients (Nitrogen, Phosphorus, Potassium)
- `temperature`: Average temperature (°C)
- `humidity`: Relative humidity (%)
- `ph`: Soil pH value
- `rainfall`: Rainfall (mm)
- `label`: Crop type (22 possible crops)

## 🧠 Machine Learning Models Used

Trained and evaluated the following ML models on the dataset:

- **Logistic Regression** – Accuracy: 91.81%
- **Gaussian Naive Bayes** – Accuracy: **99.54%** ✅ (Best model)
- **Support Vector Classifier (SVC)** – Accuracy: 96.81%
- **K-Nearest Neighbors (KNN)** – Accuracy: 96.81%
- **Decision Tree Classifier** – Accuracy: 98.86%
- **Extra Tree Classifier** – Accuracy: 90.45%
- **Random Forest Classifier** – Accuracy: 99.31%
- **Bagging Classifier** – Accuracy: 98.63%
- **Gradient Boosting Classifier** – Accuracy: 98.18%
- **AdaBoost Classifier** – Accuracy: 9.54% (Underperformed)

The best-performing model, **GaussianNB**, was selected for final crop recommendations.

## 🧪 Example Prediction

Input values:
```
N = 59, P = 69, K = 80  
Temperature = 19.07°C  
Humidity = 17.86%  
pH = 8.165  
Rainfall = 69.406 mm
```
📌 **Recommended Crop:** `chickpea`

## 🔗 GitHub Repository

Explore the code and dataset here: [Crop Recommendation GitHub Repo](https://github.com/Arpita23r/cropRecom)

## 🚀 Future Plans

I aim to enhance this project into a full web application that includes:
- ✅ **Crop Recommendation System**
- 🌿 **Plant Disease Detection** using Deep Learning (CNNs)

Currently upskilling in **Convolutional Neural Networks** and **Deep Learning** to integrate these features effectively.
