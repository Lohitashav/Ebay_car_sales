# Analyzing Used Cars Listing on eBay Kleinanzeigen
This project analyzes a dataset of used car listings from eBay Kleinanzeigen, the classifieds section of the German eBay website. The dataset was originally scraped by a Kaggle user, orgesleka, and is now available on Data.World.

# Project Objectives
The goal of this project is to clean, explore, and derive insights from the dataset. By working with real-world, messy data, this project highlights key data analysis techniques, including:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Identifying patterns and trends in the used car market
  
# Dataset Overview
Source: eBay Kleinanzeigen used car listings dataset (originally scraped and uploaded to Kaggle)
Sample size: 50,000 listings
The dataset contains information about various used car listings, including:

- Car models
- Price
- Mileage
- Registration year
- Location
- Ad details

# Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib/Seaborn (for visualizations)
- Jupyter Notebook
  
# Key Highlights
- Insights into pricing trends based on car make and model.
- Analysis of car attributes, such as mileage and registration year, to identify patterns.
- Identification and handling of outliers and anomalies in the dataset.
- Cleaning of erroneous or inconsistent data entries.


# Steps Involved
1. Cleaning Columns:
   
Renamed columns for better readability and usability.
Dropped unnecessary or duplicate columns that don’t contribute to analysis.

2. Initial Data Exploration & Cleaning:
   
Explored the dataset to understand the distribution of values, missing data, and anomalies.
Handled missing and incorrect data, addressing extreme outliers in features like price and mileage.

3. Exploring Odometer and Price columns:
   
Cleaned and analyzed the Odometer and Price columns.
Identified outliers and dropped unrealistic values (e.g., extremely high or low prices).

4. Exploring Date column:
   
Parsed and analyzed date columns (e.g., listing date) to ensure valid formats.
Investigated any inconsistencies or missing dates.

5. Dealing with Incorrect Registration Year Data:
   
Handled incorrect registration_year data, identifying and addressing invalid entries.
Dropped or corrected registration years outside a realistic range for car listings.

6. Exploring Price by Brand:
   
Analyzed price distribution by car brands to identify trends and patterns.
Visualized which car brands hold higher resale values and potential outliers in pricing.

7. Exploring Mileage:
   
Investigated how car mileage varies across different brands.
Explored correlations between price and mileage to understand factors impacting used car prices.
  
# Instructions for Running the Notebook
- Download the dataset from Data.World (if not already included).
- Ensure you have Python installed with the required libraries (pandas, numpy, matplotlib, etc.).
- Open the Jupyter Notebook and run each cell sequentially.

# Conclusion
This project demonstrates the ability to work with real-world datasets and derive meaningful insights. It showcases data cleaning and analysis skills, making it a valuable learning experience for anyone interested in data science or analytics.
