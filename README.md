# SpaceX Falcon 9 Launch Success Prediction

## Overview

This project analyzes SpaceX launch data to predict whether the Falcon 9 first stage will successfully land. The project follows a complete data science workflow from data collection to machine learning modeling.

---

## Business Objective

Accurately predicting rocket landing success can help reduce costs and improve decision-making in aerospace operations.

---

## Project Workflow

### 1. Data Collection

* SpaceX API data
* Web scraping

### 2. Data Wrangling

* Cleaning and formatting datasets
* Handling missing values

### 3. Exploratory Data Analysis (EDA)

* Launch success rates
* Relationships between payload, orbit, and outcomes

### 4. SQL Analysis

* Querying structured data for insights

### 5. Data Visualization

* Interactive maps (Folium)
* Charts and graphs

### 6. Machine Learning

* Classification models to predict launch success
* Model comparison and evaluation

---

## Tools & Technologies

* Python
* Pandas, NumPy
* Scikit-learn
* SQL
* Plotly / Folium
* Jupyter Notebooks

---

## Results

* Best model: (Fill this in)
* Accuracy: XX%
* Key factors influencing success:

  * Payload mass
  * Orbit type
  * Launch site

---

## Visualizations

* Launch site success rates
* Payload vs outcome
* Interactive map of launch locations

(Add screenshots to `/images` and link them here)

---

## How to Run

```bash
git clone https://github.com/ChrisACr/IBM_DS_Capstone_Project.git
cd IBM_DS_Capstone_Project
pip install -r requirements.txt
jupyter notebook
```

---

## Project Structure

```
IBM_DS_Capstone_Project/
│
├── data/
├── notebooks/
├── images/
├── sql/
├── README.md
└── requirements.txt
```

---

## Key Insights

* Launch success is strongly influenced by payload characteristics
* Certain launch sites show higher success rates
* Machine learning models can effectively predict outcomes

---

## Future Improvements

* Incorporate real-time data
* Improve model tuning
* Deploy as a web app or dashboard
