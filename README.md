# 🚀 IBM Data Science Capstone – SpaceX Launch Analysis

Welcome to the final project of the IBM Data Science Professional Certificate — Falcon 9 Landing Success Prediction and Analysis

<p align="center"> <img src="visuals/dashboard_screenshot.png" width="900" alt="SpaceX Dashboard"> </p>

## 📄 Summary
This capstone project is the culmination of the IBM Data Science Professional Certificate program.
The goal: predict whether the SpaceX Falcon 9 first-stage rocket will successfully land.
We explore the entire data science workflow—from data gathering to dashboard development and ML model comparison.

This repository focuses on analyzing and visualizing SpaceX launch data using web scraping, data wrangling, SQL, data visualization, machine learning, and an interactive dashboard built with Plotly Dash.

📍 Full dashboard and machine learning workflow built from scratch using real-world SpaceX launch data.

## 📚 Table of Contents

1. Problem Statement

2. Project Structure

3. Methodology

4. Dashboard Preview

5. Modeling & Results

6. Key Skills & Tools

7. Certificate

## 🎯 Problem Statement
SpaceX drastically reduces launch costs by recovering and reusing rocket boosters.
Can we predict whether a Falcon 9 first-stage will land successfully and visualize the factors that influence success?

This solution empowers decision-making for bidding, cost estimation, and evaluating launch feasibility.

## 🗂 Project Structure
bash
Copy
Edit
IBM-Data-Science-Capstone-SpaceX/
├── data/                 # Clean & final datasets
│   ├── spacex.csv
│   └── spacex_launch_geo.csv
│
├── data-collection/      # Raw data, SQL notebooks, API & scraping
│   ├── *.ipynb, *.csv
│
├── notebooks/            # Main ML & EDA notebooks
│   ├── EDA_SpaceX.ipynb
│   ├── SQL_Analysis.ipynb
│   └── ML_Modeling.ipynb
│
├── dashboard/            # Interactive Plotly Dash App
│   ├── spacex_dash_app.py
│   └── spacex_launch_dash.csv
│
├── visuals/              # Images used in README or slides
│   ├── dashboard_screenshot.png
│   ├── confusion_matrix.png
│   └── folium_map.png
│
├── presentation/         # Final report
│   ├── IBM_Capstone_SpaceX_Report.pptx
│   └── IBM_Capstone_SpaceX_Report.pdf
│
└── README.md

## 🔍 Methodology
1. Data Collection
✅ SpaceX Launch API (REST)

✅ Web scraping from Wikipedia

✅ SQL-based dataset joins

2. Data Wrangling
Removed nulls, merged launch site data, and feature engineering for success labels.

3. Exploratory Data Analysis
Launch trends across years, orbits, and payload ranges.

Correlations between booster versions and outcomes.

SQL queries on launch frequencies and success rates.

4. Dashboard Development
Built an interactive web app using Plotly Dash.

Includes dynamic pie charts, sliders, and scatter plots.

5. Machine Learning
Preprocessing: Normalization, encoding

Models built:

Logistic Regression

Support Vector Machine

Decision Tree Classifier

K-Nearest Neighbors (KNN)

GridSearchCV for hyperparameter tuning

## 📊 Dashboard Preview
Run the Dash app locally:

bash
Copy
Edit
cd dashboard
python spacex_dash_app.py
Navigate to: http://localhost:8050

Key Features:

✅ Filter by launch site

✅ Select payload range

✅ Visualize payload-success relationships

<p align="center"> <img src="visuals/dashboard_screenshot.png" width="800" alt="Dash App Screenshot"> </p>

## 🧠 Modeling & Results
Algorithm	Accuracy (Test)	Best CV Score
Logistic Regression	0.84	0.86
Support Vector Machine	0.82	0.84
Decision Tree Classifier	0.85	0.87
K Nearest Neighbors	0.83	0.85

## 🎯 Best Performing Model: Decision Tree Classifier with 87% cross-validation accuracy.

<p align="center"> <img src="visuals/confusion_matrix.png" width="500" alt="Confusion Matrix"> </p>

## 🛠 Key Skills & Tools
Languages: Python, SQL

Libraries: Pandas, NumPy, Plotly, Scikit-Learn, Matplotlib, Seaborn, BeautifulSoup

Dashboards: Plotly Dash (interactive visualization)

Maps: Folium

ML Techniques: Classification, GridSearchCV, Confusion Matrix, Accuracy Comparison

Version Control: Git & GitHub

## 🏅 Certificate
This project was submitted as part of:

<p align="center"> <a href="https://coursera.org/share/YOUR-LINK-HERE"><img src="https://user-images.githubusercontent.com/84391594/161432000-ba6916f0-6f5e-49ab-9ff3-fae4f6f18596.png" height="300" alt="Coursera Certificate"></a> </p>

🙋‍♂️ Author
Made with 💡 by Ankush Owdhball
For the IBM Data Science Professional Certificate

GitHub: @Ankushowdhball

LinkedIn:
