# Global Smartphone Pricing Analysis

##  Overview
This project explores smartphone pricing and technical specifications across five countries: **Pakistan, India, China, USA, and Dubai**. The goal is to analyze how product features (such as RAM, battery, and screen size) influence launch price, and how pricing compares across regions after normalizing for currency.

---

## Objectives
- Clean and preprocess messy, unstructured data
- Convert international prices to USD using fixed exchange rates
- Perform **exploratory data analysis (EDA)** to uncover trends
- Apply **hypothesis testing** to compare prices across countries
- Build a **machine learning model (linear regression)** to explore feature-price relationships

---

##  Tools & Libraries
- **Python**
- **Pandas** – for data cleaning, transformation, and basic visualizations
- **Statsmodels** – for hypothesis testing using `ztest`
- **Scikit-learn** – for building and evaluating a linear regression model
- **Jupyter Notebook** – for development and presentation

---

##  Features
- Extracted numeric values from text-based fields (ex: "2,000 mAh" → 2000)
- Standardized local currency prices into USD for cross-market comparison
- Conducted EDA to identify trends in pricing and product specifications
- Performed statistical tests to validate pricing differences
- Built a linear regression model to predict launch price based on technical features

---

##  Dataset
The dataset was sourced from Kaggle - (https://www.kaggle.com/datasets/abdulmalik1518/mobiles-dataset-2025) and includes smartphone specifications and launch prices from multiple countries.  
It is shared under the **Apache 2.0 License** and included in this repository for educational purposes.

> **Credit:** Original dataset by Abdul Malik on Kaggle.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/smartphone_analysis.git
   cd smartphone_analysis
