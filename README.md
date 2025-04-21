# capstoneprojectrepo
# SpaceX Launch Analysis Capstone Project

Welcome to my Data Science Capstone Project! This project aims to analyze SpaceX launch data to gain insights into their launch success trends, site performance, and identify key factors affecting successful landings. 

---

## Table of Contents
- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Data Wrangling](#data-wrangling)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Interactive Visualizations](#interactive-visualizations)
- [Machine Learning & Predictive Modeling](#machine-learning--predictive-modeling)
- [Project Structure](#project-structure)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [License](#license)

---

## Project Overview
This project explores SpaceX's launch history using data collected from multiple sources including REST APIs and web scraping. The goal is to:
- Track launch performance across sites and years
- Visualize key metrics and trends interactively
- Predict the success of Falcon 9 first stage landings

---

## Data Collection
- Launch records were retrieved using **REST API** calls from SpaceX's open API.
- Supplementary data (e.g., payload mass, landing outcome) was scraped from **Wikipedia** tables using **BeautifulSoup**.

---

## Data Wrangling
- Cleaned and merged datasets
- Handled missing values and inconsistent formats
- Engineered features like `Landing Outcome`, `Success Class`, and converted categorical variables

---

## Exploratory Data Analysis (EDA)
EDA was performed using:
- **SQL**: to analyze launch patterns, payload distributions, and site-specific metrics
- **Seaborn**/**Matplotlib**: to generate key charts for correlation and trends

---

## Interactive Visualizations
- **Folium**: Mapped launch sites and proximity to coastlines, highways, and cities
- **Plotly Dash App**: Enabled users to explore:
  - Launch success by site
  - Payload correlation with mission outcome
  - Booster version performance

---

## Machine Learning & Predictive Modeling
Classification models were trained to predict the likelihood of a successful landing:
- **Logistic Regression**
- **SVM (Support Vector Machine)**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**

Each model was tuned using **GridSearchCV** and evaluated using:
- Accuracy score
- Confusion matrix

---

## Project Structure
```bash
├── Data_Collection.ipynb
├── Web_Scraping.ipynb
├── EDA_SQL.ipynb
├── Interactive_Maps.ipynb
├── Dashboard_App.py
├── ML_Modeling.ipynb
├── dataset_part_2.csv
├── dataset_part_3.csv
├── spacex_launch_dash.csv
├── README.md
```

---

## Conclusion
This project demonstrates how various data science techniques can be integrated to deliver actionable insights in the aerospace domain. We explored SpaceX’s launch history, visualized spatial and performance trends, and built models to support future mission planning.

---


---

## License
This project is for educational purposes under the IBM Data Science Capstone guidelines.

