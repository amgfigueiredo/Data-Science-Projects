# SpaceX Falcon 9 Landing Prediction

## 📌 Project Overview

SpaceX revolutionized the space industry with reusable rockets, significantly lowering launch costs. This project aims to predict the success of Falcon 9's first-stage landing using machine learning techniques. By analyzing launch conditions, payloads, and orbital details, we provide insights that can assist competitive space ventures in planning cost-effective missions.

## 📊 Key Objectives

- Utilize SpaceX API & Web Scraping for data collection.

- Perform Exploratory Data Analysis (EDA) using SQL, Pandas, Matplotlib & Seaborn.

- Create Interactive Visual Analytics using Folium & Dash.

- Implement Machine Learning Models to predict successful landings.

## 📂 Project Structure

📦 CapstoneProject/SpaceX

 ┣ 📂 data_collection
 
 ┃ ┣ 📜 01-data-collection-api-spacex.ipynb
 
 ┃ ┗ 📜 02-webscraping-spacex.ipynb
 
 ┣ 📂 data_wrangling
 
 ┃ ┗ 📜 03-data-wrangling-spacex.ipynb
 
 ┣ 📂 exploratory_analysis
 
 ┃ ┣ 📜 04-EDA-SQL.ipynb
 
 ┃ ┣ 📜 05-EDA-with-Visualization.ipynb
 
 ┃ ┗ 📜 06-Launch-Sites-Locations-Analysis-Folium.ipynb
 
 ┣ 📂 interactive_dashboard
 
 ┃ ┗ 📜 07-spacex_app.py
 
 ┣ 📂 machine_learning
 
 ┃ ┗ 📜 08-SpaceX_Machine_Learning_Prediction.ipynb
 
 ┗ 📜 README.md


## 📥 Data Collection

✔ API Extraction: Data collected via GET request to the SpaceX API.
✔ Web Scraping: Falcon 9 launch records retrieved from Wikipedia using BeautifulSoup.
✔ Data Wrangling: Cleaned and formatted dataset using Pandas, handling missing values.

🔗 SpaceX API Data Collection Notebook
🔗 Web Scraping Notebook

## 📈 Exploratory Data Analysis (EDA)

✔ EDA with SQL: Analyzed mission success/failure, launch sites, payload masses.

✔ EDA with Visualization: Identified success trends based on flight number, orbit type.

✔ Folium Map Analysis: Interactive geospatial visualization of launch success rates.


🔗 SQL-Based EDA
🔗 Data Visualization Notebook
🔗 Folium Map Analysis

## 📊 Interactive Dashboard

✔ Built with Plotly Dash to visualize launch site performance.

✔ Includes scatter plots, pie charts showing success rates by payload and site.

🔗 Dashboard Code

## 🤖 Machine Learning Model

✔ Feature Engineering: One-hot encoding applied for categorical variables.

✔ Model Training: Evaluated Decision Tree, KNN, SVM, and Logistic Regression models.

✔ Hyperparameter Tuning: Optimized using GridSearchCV.

✔ Best Model: Decision Tree achieved the highest classification accuracy.

🔗 Machine Learning Notebook

## 🔍 Key Insights

- KSC LC-39A had the highest launch success rate (76.9%).

- More launches per site correlate with higher success rates.

- Low Earth Orbit (LEO) flights show strong correlation with success.

- Decision Tree is the most effective classification model for this dataset.

## 📌 Conclusion

This project successfully predicts Falcon 9 first-stage landings, providing valuable insights for space mission planning. By leveraging data science and machine learning, we offer a decision-support tool for the aerospace industry.

## 💡 Want to explore the full project? Check it out on GitHub!

📢 Give this repo a ⭐ if you found it useful! 🚀


