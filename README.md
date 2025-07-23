# Steam Games Dashboard & Data Analysis

This repository contains a data cleaning workflow implemented in Python and an interactive Power BI dashboard designed to analyze the Steam Games dataset sourced from [Kaggle](https://www.kaggle.com/datasets/fronkongames/steam-games-dataset/data).

---

## Dataset

- **Source:** [Steam Games Dataset on Kaggle](https://www.kaggle.com/datasets/fronkongames/steam-games-dataset/data)
- **Description:** Metadata for over 70,000 Steam games, including titles, publishers, release dates, genres, tags, pricing, reviews, supported platforms, ownership estimates, and more.
- **Period Covered:** 2013 – 2025

---

## Technologies Used

- **Python**: Data cleaning, preprocessing, and analysis
  - **Pandas:** Data manipulation and wrangling
  - **NumPy:** Numerical computations
  - **Matplotlib**/**Seaborn:** Data visualization during EDA
  - **Jupyter Notebook:** Interactive scripting environment
- **Power BI:** Dashboard creation and interactive analytics
- **CSV:** Data exchange format between workflow stages
- **Kaggle:** Data source and initial exploration environment

---

## Project Overview

This project focuses on:

- Cleaning and preprocessing raw Steam game data using Python.
- Engineering relevant features for analysis.
- Creating an interactive Power BI dashboard to explore trends and insights.
- Extracting actionable information relevant to the Steam gaming ecosystem.

---

## Data Cleaning and Preparation

Data preparation was conducted in a Jupyter notebook with the following key steps:

- Removal of duplicate entries and handling of missing values.
- Standardization and normalization of genre, tag, and category fields.
- Conversion and parsing of release dates and price columns.
- Encoding of platform support (Windows, Mac, Linux) as binary indicators.
- Export of the cleaned dataset in CSV format for use in the Power BI dashboard.

---

## Dashboard Overview

The Power BI dashboard presents interactive views and breakdowns of:

- Game releases by year
- Genre, tag, and category distributions
- Leading publishers and their title counts
- Platform support across Windows, Mac, and Linux
- Pricing trends and review patterns
- Ownership and concurrent player estimates

---

## Dashboard Summary

- **Total Games Analyzed:** ~71,000  
- **Average Price:** $8.08  
- **Average Owners per Game:** 85,000  
- **Top Genre (by count):** Indie  
- **Top Owned Game:** Dota 2

**Note:** Although *Counter-Strike: Global Offensive* (now *Counter-Strike 2*) is one of the most played and owned games on Steam, it was officially listed on the platform in **2012**. Since the dataset primarily covers games released **from 2013 onward**, Counter-Strike is not included in the analysis. If it were, it would likely top the ownership leaderboard by a significant margin.

---

## Key Insights

- **Growth Pattern:** Steam experienced rapid growth in the number of new game releases from 2017 to 2022, with a notable decline beginning in 2023.
- **Genre Trends:** Indie games dominate the platform by volume and also demonstrate strong player engagement. Other prominent genres include Action, Casual, and Adventure.
- **Platform Support:** Approximately 74% of games support Windows. MacOS and Linux support remain limited, at around 15% and 10% respectively.
- **Pricing:** The majority of titles are affordably priced, with a median of around $8.
- **Review Trends:** The years 2017 to 2019 saw the highest concentration of positive user reviews.
- **Publisher Influence:** Leading publishers such as CAPCOM, Electronic Arts, and Ubisoft rank highest in terms of average concurrent players and engagement levels.

---


<img width="1669" height="929" alt="Power BI Dashboard Screenshot Page 1" src="https://github.com/user-attachments/assets/b7c61b95-7fb8-4227-8415-165c052b6bca" />

<img width="1659" height="929" alt="Power BI Dashboard Screenshot Page 2" src="https://github.com/user-attachments/assets/eed38565-452d-4fea-9148-134470d97abd" />


