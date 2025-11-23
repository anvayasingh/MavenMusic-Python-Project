# Maven Music Dataset Analysis

# Project Overview
This project analyzes the **Maven Music** dataset consisting of:
- Customer demographic information
- Track listening history

The goal is:
- To clean and explore both datasets
- To understand listening behavior
- To prepare the data for a **supervised ML model** that predicts user preferences.

# Data Used
- `maven_music_customers.csv`
- `maven_music_listening_history.xlsx`

# Key Steps & Workflow

# 1. Data Gathering
- Loaded customer dataset (CSV)
- Loaded listening history (Excel)
- Inspected structure using `.head()`, `.info()`, `.describe()`

# 2. Data Cleaning
- Removed unnecessary columns  
- Handled missing values  
- Standardized data types  
- Merged customer & listening history datasets for unified analysis  

# 3. Exploratory Data Analysis (EDA)
Performed detailed EDA including:
- Distribution of artists/tracks
- Total listening time per user
- Most popular genres / artists
- Customer segments based on usage

# 4. Model Preparation
- Encoded categorical variables  
- Engineered features such as:
  - Total listens
  - Unique artists heard
  - Most played artist
- Prepared **train/test** splits for supervised learning

# Visualizations
Built using:
- **Matplotlib**
- **Seaborn**

Charts include:
- Count plots  
- Bar charts  
- Distribution plots  
- Time-based listening patterns  

# Tech Stack
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib

# How to Run
  pip install pandas numpy matplotlib seaborn
  Open `MavenMusic.ipynb` in Jupyter and run all cells.

# Key Insights
- Certain artists dominate listening patterns.
- Customers with more active listening behavior exhibit clearer preference signals.
- The dataset is suitable for a **recommendation system or ML classification model**.

