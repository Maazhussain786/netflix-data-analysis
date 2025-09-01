# Netflix Content Analysis  

This project explores the **Netflix Titles dataset** (from Kaggle) using **Pandas** for data cleaning and **Matplotlib** for visualizations.  
The goal is to uncover insights about Netflix’s catalog — including the balance between Movies and TV Shows, content ratings, durations, release trends, and country contributions.  

---

## Features  

- **Data Cleaning**  
  - Removed null values in important fields (title, director, cast, etc.)  
  - Extracted numeric durations from movie runtime strings (e.g., `"90 min"` → `90`).  

- **Visualizations**  
  - Bar chart: Movies vs TV Shows count  
  - Pie chart: Distribution of content ratings  
  - Histogram: Movie duration distribution  
  - Scatter plot: Content released by year  
  - Horizontal bar chart: Top 10 countries by number of shows  
  - Line plots: Movies vs TV Shows released per year  

---

## Repository Structure  

## Dataset  

- Source: [Netflix Titles Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  

---

## Technologies Used  

- Python  
- Pandas  
- Matplotlib  

---

## Insights Gained  

- Netflix hosts more Movies than TV Shows.  
- TV-MA is the most common rating.  
- Most movies have durations between 80–120 minutes.  
- Content production has grown significantly after 2015.  
- The United States, India, and United Kingdom contribute the most titles.  
