# AQI-Prediction
# 🌍 Air Quality Prediction Dashboard

This is a machine learning dashboard built with *Streamlit* for *predicting AQI (Air Quality Index)* based on pollutant levels using real-world data. The goal was to make air quality predictions accessible through a user-friendly web app, while demonstrating proficiency in data analysis, model building, and UI deployment.

---

## ✅ My Contribution

I was solely responsible for:
- Designing the Streamlit-based interactive dashboard.
- Implementing the entire ML pipeline using RandomForestRegressor.
- Performing data cleaning and feature engineering.
- Visualizing insights using Plotly.
- Creating model evaluation visuals (residuals, predicted vs actual).
- Integrating user AQI predictions using custom input.
- Handling model persistence with joblib.
- Excluding heavy files with .gitignore and maintaining clean Git practices.

---

## 🔍 Project Overview

| Sprint Phase              | Objective                                                                 |
|---------------------------|---------------------------------------------------------------------------|
| Sprint 1                  | Data ingestion, pre-processing, visualization setup                       |
| Sprint 2                  | Model training with Random Forest, model evaluation metrics               |
| Sprint 3                  | Streamlit frontend, interactive features (EDA vs Prediction mode)         |
| Sprint 4                  | AQI prediction input form, lag feature, dynamic plotting                  |
| Sprint 5                  | Styling, bug fixing, .gitignore handling, and GitHub deployment setup     |

---

## 🧩 Summarized User Stories / Tasks

| Task                                              | Status  | Notes                                |
|---------------------------------------------------|---------|---------------------------------------|
| Load & clean AQI dataset                          | ✅       | Implemented caching, forward filling  |
| EDA plots (histogram, line, box, heatmap)         | ✅       | Built with Plotly Express + Go        |
| Model training pipeline                           | ✅       | Sklearn-based, saved with joblib      |
| AQI Prediction input panel                        | ✅       | Interactive form with lag feature     |
| Model evaluation + residuals                      | ✅       | RMSE, R², scatter vs ideal line       |
| UI styling with custom CSS                        | ✅       | Brand-consistent & clean              |
| GitHub integration (.gitignore, clean commits)    | ✅       | Excluded heavy CSVs & models          |

---

## 📸 Images

| EDA Dashboard                                

| ![EDA](images/intereface.jpg)               



---

---

## 🧾 Code Access

You can explore the core project files directly through the GitHub repository:

- 🔧 [*Main Application Code (app.py)*](https://github.com/RaviSpacex/AQI-Prediction/blob/main/app.py)  
  Contains all logic for data processing, EDA, model training, and AQI prediction via Streamlit.

- 🖼️ [*Images Folder*](https://github.com/RaviSpacex/AQI-Prediction/tree/main/images)  
  Includes visual assets and screenshots used in the README and UI documentation.

Feel free to clone or fork the repo to explore and build on the project.

---

## 🧠 Tech Stack

- Python, Pandas, Numpy
- Scikit-learn for modeling
- Streamlit for app UI
- Plotly for data visualization
- joblib for model persistence
- GitHub for version control

---

## 📂 Repo Structure

```
📦 air_quality_prediction/
├── app.py
├── combined_daily_data.csv
├── saved_models/       
├── images/             
│   ├── interface.jpg
│   
├── .gitignore
├── README.md
