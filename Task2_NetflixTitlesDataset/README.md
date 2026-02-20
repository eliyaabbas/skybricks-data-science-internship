# 🎬 Task 2: Netflix Titles Dataset - EDA

## 📝 Overview
This repository contains the solution for **Task 2: Netflix Titles Dataset Exploratory Data Analysis**, part of the SkyBricks Data Science Internship. The objective of this task is to perform an in-depth data exploration of Netflix's catalog to uncover trends in content creation, geographical distribution of content, ratings, and variations between Movies and TV Shows.

## 📁 Files in this Task
* **`netflix_titles.csv`**: The raw Netflix dataset containing 8,807 titles and 12 features describing the show type (Movie/TV Show), director, cast, country, release year, rating, duration, and listed genres.
* **`Netflix_EDA.ipynb`**: The primary Jupyter Notebook documenting all steps taken to clean, process, and analyze the titles dataset.
* **`Netflix_Cleaned_Task2_Final.csv`**: The cleansed dataset resulting from data wrangling tasks (e.g., handling nulls, standardizing formats).
* **`Project_Comparison_Deck_Styled.pptx`**: A presentation deck detailing the comparisons, trends, and key findings from the EDA phase.

## 🎯 Objectives Achieved
1. **Data Cleaning**: 
   - Addressed missing values across columns like `director`, `cast`, and `country`.
   - Reformatted columns such as `date_added` into proper datetime structures.
2. **Feature Engineering**:
   - Extracted added Year and Month to view seasonal trends.
   - Parsed durations into numeric values for comparative analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of content (Movies vs. TV Shows).
   - Uncovered growth trends in content acquisition across decades.
   - Profiled titles by country and target audience (ratings).

## 🚀 How to Run
1. Install prerequisites (`pandas`, `matplotlib`, `seaborn`, `numpy`).
2. Open `Netflix_EDA.ipynb` in a Jupyter environment.
3. Run all cells from top to bottom to witness the distribution charts and insights.

## 📈 Key Insights
* Movies comprise the majority of the current Netflix catalog, although TV Shows represent a rapidly growing segment.
* Distinct seasonal and geographical patterns influence Netflix's global content strategy.
