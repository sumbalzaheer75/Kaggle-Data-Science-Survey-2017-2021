# Kaggle-Data-Science-Survey-2017-2021
Data cleaning, categorical handling, and insight generation from the Kaggle Data Science Survey (2017–2021). Includes demographic analysis, programming language trends, and visualization using Python.

# Kaggle Data Science Survey (2017–2021) — Data Cleaning & Insights

## Project Overview
This project analyzes the Kaggle Data Science Survey to extract meaningful insights about respondents' demographics, education, roles, and tool preferences. The dataset contains **293 columns** and required careful cleaning to avoid accidental data loss.

## Objectives
- Clean a real-world dataset containing missing values, duplicates, and inconsistent formatting.  
- Handle categorical variables without losing information.  
- Extract key insights about respondents' behavior and preferences.  
- Visualize findings with clear and appealing charts.  

## Data Cleaning  
- Removed extra descriptive rows and standardized headers (`Q1`, `Q2`, …).  
- Normalized categorical fields:
  - Gender mapped into **Male / Female / Other**
- Trimmed whitespace, fixed inconsistent labels, and dropped duplicate records.  
- Applied label encoding for optional modeling tasks.  

## Insights
- **Top respondent countries**  
- **Gender distribution**  
- **Age group breakdown**  
- **Most common job roles in data science**  
- **Highest education levels**  
- **Most popular programming languages**  
- **Most popular IDEs and tools**  

## Key Findings
- Most respondents are students or young professionals in their 20s and 30s.  
- Male participation dominates, though female and other categories are notable.  
- The majority have a bachelor's or master's degree.  
- **Python, SQL, and R** are the top programming languages.  
- **Jupyter Notebook, VS Code, and PyCharm** are the most popular tools.  
- Respondents are primarily concentrated in a few major countries.  

## Tools Used
- **Python:** pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook:** data cleaning, EDA, visualization  
