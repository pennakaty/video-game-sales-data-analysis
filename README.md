# Global Video Game Sales Analysis 🎮

This repository contains a comprehensive data cleaning and exploratory analysis of the **Global Video Game Sales** dataset. The project focuses on processing historical gaming data to extract insights regarding regional sales trends, critic evaluations, and market performance.

## 📌 Project Overview
The main goal of this project was to take a raw dataset containing over 6,800 records and perform a thorough data preparation pipeline. This includes quantitative description, handling missing values, and preparing the data for visualization.

## 📊 Dataset Specifications
The analysis is performed on `Global_Video_Game_Sales.csv`, which includes:
* **Records:** 6,894 titles
* **Features:** 15 columns including Name, Year of Release, Genre, Publisher, regional sales (NA, EU, JP, Other), Global Sales, and scores (Critic/User).
* **Timeframe:** Data spanning from 1985 to 2016.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `Pandas`: Data manipulation and cleaning.
    * `NumPy`: Numerical operations.
    * `Matplotlib` & `Seaborn`: Data visualization.

## 📈 Key Workflow
1. **Initial Exploration:** Loading data and identifying the structure/shape of the dataset.
2. **Descriptive Statistics:** Analyzing means, standard deviations, and quartiles for sales and scoring metrics.
3. **Data Cleaning:** Identifying and treating null values and ensuring data consistency.
4. **Insights:** Comparing critic vs. user scores and analyzing regional market dominance.

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have the following dependencies installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
