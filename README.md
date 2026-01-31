# Innomatics GenAI Hackathon – Food Delivery Dataset Analysis

## Overview
This repository contains the solution for the **Advanced GenAI Internship Hackathon** conducted by Innomatics Research Labs.  
The goal was to analyze a food delivery dataset combining orders, users, and restaurants to understand revenue trends, user behavior, city- and cuisine-wise performance, membership impact, and seasonality.

## Files
- `food_delivery_analysis.ipynb` – Jupyter Notebook containing all code, analysis, and answers for:
  - MCQs
  - Numerical questions
  - Fill-in-the-blank questions
- `final_food_delivery_dataset.csv` – Final merged dataset combining orders, users, and restaurant information.  
- `restaurants.sql` – SQL file used to create the `restaurants` table in SQLite (optional if you included `restaurants.db`).  

## Notebook Structure
1. **Imports & Setup** – Import required libraries (`pandas`, `numpy`, `sqlite3`).  
2. **Data Loading** – Load CSV (`orders.csv`), JSON (`users.json`), and SQL (`restaurants.sql`) datasets.  
3. **Data Merging** – Merge datasets using `user_id` and `restaurant_id` with left joins to create the final dataset.  
4. **Exploratory Analysis** – Analyze:
   - Total revenue per city, cuisine, and membership type  
   - Average order value  
   - Restaurant performance based on ratings  
   - User behavior patterns  
   - Seasonal trends and quarterly revenue  
5. **MCQs & Numerical Questions** – Compute answers for all questions provided in the hackathon form.  
6. **Fill-in-the-Blank Questions** – Answered using insights from the dataset.  
7. **Conclusion & Insights** – Summary of key observations from the dataset analysis.  

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your_username/Innomatics_GenAI_Hackathon.git
