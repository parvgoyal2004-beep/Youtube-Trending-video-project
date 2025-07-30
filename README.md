
# YouTube Trending Videos Analysis

<img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" width="350">

## Project Overview

This project performs an **Exploratory Data Analysis (EDA)** and builds machine learning models to predict trending status on a simulated dataset of YouTube trending videos. Inspired by the EDA style of the [Black Friday Sales EDA Project](https://github.com/piyush-pankaj/Black-Friday-Sales), this notebook is fully documented, includes attractive visuals, and covers all key data science steps.

---

## Dataset

- **Rows:** 10,000
- **Columns:** 6  
    - `views`: Number of video views (int)
    - `likes`: Number of likes (int)
    - `comments`: Number of comments (int)
    - `category`: Video category (str: Music, Sports, News, Gaming, Education)
    - `channel`: Channel name (str: Channel_1 ... Channel_100)
    - `trending`: Target (int: 1 if trending/viral, 0 if not)

*The dataset is simulated for academic/project purposes.*

---

## Project Outline

1. **Introduction**
    - What is EDA?
    - Project goals and dataset description
2. **Data Loading & Overview**
    - Import libraries
    - Show first rows, check nulls, datatypes, value counts
3. **Data Preparation**
    - Cleaning, encoding, and feature engineering
4. **Exploratory Data Analysis**
    - Four diverse visualizations
        - Barplot: Trending rate by category
        - Histogram: Views distribution
        - Boxplot: Likes by category
        - Heatmap: Feature correlation
    - Insights with markdown and images
5. **Machine Learning**
    - Train/test split and scaling
    - Fit and evaluate **4 ML models**:
        - Logistic Regression
        - Random Forest
        - K-Nearest Neighbors (KNN)
        - Support Vector Machine (SVM)
    - Compare model performances
6. **Conclusion**
    - Summary of findings
    - Visual thanks

---

## References

- Notebook structure and documentation inspired by [Black Friday Sales EDA](https://github.com/piyush-pankaj/Black-Friday-Sales/blob/main/eda-on-black-friday-sales-dataset.ipynb)
- Images: 
    - [YouTube Logo](https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg)
    

---

## License

This project is for educational purposes only.
