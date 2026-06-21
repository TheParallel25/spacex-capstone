# SpaceX Falcon 9 Launch Analysis (IBM Capstone Project)

## Project Overview
This project analyzes SpaceX Falcon 9 launch data to predict whether the first stage of the rocket will land successfully. The goal is to identify key factors influencing mission success using data science techniques.

---

## Data Sources
- SpaceX REST API
- Web scraping from Wikipedia Falcon 9 launch records

---

## Methods Used

### Data Collection
- Retrieved launch data using SpaceX REST API
- Scraped additional launch records from Wikipedia
- Converted JSON and HTML data into structured pandas DataFrames

### Data Wrangling
- Cleaned missing values
- Filtered irrelevant records (Falcon 1 removed)
- Standardized and prepared dataset for modeling

### Exploratory Data Analysis (EDA)
- Visualized launch success rates
- Analyzed payload distribution
- Studied launch site performance

### SQL Analysis
- Performed queries on launch success, payload, and site performance

### Interactive Visualizations
- Built Folium maps for launch site visualization
- Created Plotly Dash dashboard for interactive analysis

### Machine Learning Models
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors

Models were tuned using GridSearchCV and evaluated using accuracy scores.

---

## Best Model
The best performing model was selected based on test accuracy after hyperparameter tuning.

---

## Repository Contents
- Jupyter Notebook (complete analysis)
- Visualizations
- Data processing steps

---

## Author
IBM Data Science Capstone Project
