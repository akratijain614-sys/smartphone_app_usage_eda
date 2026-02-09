# Smartphone App Usage & Market Trends Analysis (EDA)
## 📊 Project Overview
This project performs an Exploratory Data Analysis (EDA) on Google Play Store app data to uncover patterns in app usage, install behavior, ratings, and monetization strategies.
The analysis focuses on understanding what drives app adoption and how factors like category, pricing (free vs paid), and ratings influence installs.

## 🎯 Objectives

-Analyze app distribution across categories
-Compare install trends between Free and Paid apps
-Study the relationship between ratings and install counts
-Identify top-performing apps within categories
-Build interactive visualizations for deeper exploration
-Apply descriptive and predictive reasoning to interpret app success factors

## 📁 Dataset

-Source: Google Play Store Apps dataset (Kaggle)
-Raw data: Stored without modification
-Processed data: Cleaned and standardized for analysis

data/
├── raw/


│   └── googleplaystore.csv


└── processed/
    └── cleaned_apps.csv

## 🧹 Data Cleaning & Preparation

-Converted installs, price, and reviews to numeric formats
-Removed symbols and inconsistent values
-Standardized column names
-Preserved raw data and saved cleaned output separately
### Cleaning logic is documented in:
01_cleaning_preparation.ipynb

## 📊 Exploratory Data Analysis (EDA)

### EDA is performed using the cleaned dataset to:
Explore category-wise app dominance

-Compare free vs paid app performance
-Analyze install ranges and average ratings
-Visualize trends using bar charts and aggregated metrics
-Enable interactive filtering by category and app type
### EDA is documented in:
02_eda_analysis.ipynb

## 📈 Key Insights
-Free apps dominate total installs across nearly all categories
-App installs are highly skewed — a small number of apps account for most downloads
-Average ratings remain consistently high across install ranges
-High ratings alone do not guarantee large-scale adoption
-Accessibility, visibility, and network effects appear to be stronger drivers of success than ratings alone

## 🧠 Analysis Approach

**Descriptive analysis** Used to summarize existing patterns in categories, installs, and ratings

**Predictive reasoning:** Applied by analyzing relationships between installs, ratings, and pricing models

No time-series forecasting was performed due to lack of temporal data

## 🛠️ Tools and Technologies Used

- **Python** –Core programming language for data analysis 
- **Pandas** – Data manipulation, filtering, and aggregation
- **Matplotlib** – Visualization
- **ipywidgets** – Interactive dropdown controls for dynamic exploration 
- **Google Colab**-Interactive analysis environment

## ▶️ How to Run

1. Clone or download this repository  
2. Open the notebooks in Jupyter Notebook or Google Colab  
3. Run `01_cleaning_preparation.ipynb` to generate the cleaned dataset  
4. Run `02_eda_analysis.ipynb` to perform exploratory data analysis

## ✅ Conclusion

This project demonstrates how structured data cleaning, exploratory analysis, and relationship-based predictive reasoning can provide meaningful insights into app market dynamics using real-world app store data.
