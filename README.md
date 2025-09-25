# Google Trends Medicine Forecasting with Deep Learning

## 📌 Project Overview
This project analyzes **Google search trends** for different medicines in India and predicts future search interest using **Deep Learning (LSTM)**.  
It helps identify:
- Top-searched medicines
- Regional interest across states
- Forecast of future search trends

The final output can be exported to **Tableau** for creating interactive dashboards.

---

## 🚀 Features
- **Google Trends Data**: Automatically fetches real-time search data using `pytrends`
- **Top Medicines Detection**: Finds top 10 most searched medicines
- **LSTM Prediction**: Forecasts future search interest using deep learning
- **Hyperparameter Tuning**: Uses **Keras Tuner** to improve model accuracy
- **Tableau Export**: Exports CSV files for advanced visualization in Tableau
- **Interactive Visualization**: Plots actual vs predicted values

---

## 📂 Dataset
- **Source**: Google Trends API (`pytrends`)
- **Region**: India
- **Medicines**: Paracetamol, Ibuprofen, Aspirin, Cetirizine, Amoxicillin, etc.
- **Time Range**: 2020-2025 (modifiable)

---

## 🧠 Deep Learning Concept Used
- **Bidirectional LSTM**: Learns sequential data patterns in both directions  
- **Dropout Layers**: Prevents overfitting  
- **EarlyStopping + Learning Rate Scheduling**: Improves training efficiency  
- **Hyperparameter Optimization**: Automatically selects best model parameters using **Keras Tuner**

---

## 🛠️ Installation
```bash
# Install dependencies
pip install pytrends pandas tensorflow scikit-learn matplotlib seaborn keras-tuner
