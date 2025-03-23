# DSA 210 Term Project: Used Car Price Prediction

## Project Overview  
This project aims to predict the price of used (2nd hand) Mercedes and Hyundai vehicles based on various factors such as model, year, mileage, fuel type, transmission, and more. By applying data science techniques, I will analyze how these attributes influence the value of the used cars.  

## Motivation

- **Personal Interest**
  
  I have a personal interest in analyzing cars for sale and in this project I am interested in used Hyundai and Mercedes vehicles. Exploring car pricing patterns and the factors that affect prices is a fascinating real world problem.
- **Application**
  
  I want to integrate this personal interest into my work in data science and this project allows me to apply machine learning techniques to a practical scenario.

## Data Source
The data that will be used in this project comes from publicly available datasets on Kaggle.
1. **Mercedes Used Car Listing**: Contains data on used Mercedes cars, including price (in euros), transmission, mileage, fuel type, road tax, miles per gallon (mpg), and engine size.
   - [Dataset Link](https://www.kaggle.com/datasets/mysarahmadbhat/mercedes-used-car-listing)

2. **Hyundai Used Car Listing**: Contains data on used Hyundai vehicles such as model, year, price (in euros), transmission, and more.
   - [Dataset Link](https://www.kaggle.com/datasets/mysarahmadbhat/hyundai-used-car-listing)

All these consistencies, such as the fact that both datasets are published by the same person, that their columns are the same, and that they use the same currency, will make the processing of the datasets easier.

## Tools & Technologies Used
- **Programming Language:** Python
- **Data Analysis & Processing:** Pandas
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn

## Data Analysis
The project follows a structured approach:
1. **Data Cleaning & Preprocessing**: 
- **Handling Missing Values:** Missing or NULL values in the datasets will be identified and addressed. Numerical columns will have missing values imputed using the mean or median, and categorical variables will be imputed with the mode or removed if the data is substantially missing.
  
- **Standardizing Formats:** All data will be standardized to ensure consistency. Numerical values (e.g., mileage, price) will be correctly formatted, and categorical variables (e.g., fuel type, transmission) will be encoded properly.

- **Removing Columns Not Common Between Datasets:** Columns that are not common between the two datasets (Mercedes and Hyundai) will be removed during the data merging process. This ensures that only the shared columns are retained, creating a larger, unified dataset for model training.
  
2. **Exploratory Data Analysis (EDA)**:
- **Visualizing Relationships:** Various visualizations will be created to understand how different attributes (e.g., mileage, fuel type, engine size) influence the car price.
  
3. **Machine Learning Models**:
- Regression techniques will be applied to predict car prices based on the cleaned and preprocessed dataset. 

## Expected Findings
- Key factors affecting price might include mileage, fuel type, and engine size.
- Different brands may have different depreciation trends based on model popularity and market demand.

## Limitations and Future Work
- The datasets may not include all factors influencing car prices, such as accident history or region-specific demand.
- Future work could include integrating more brands and economic indicators, such as inflation and fuel price trends.
- The model could be further refined using deep learning techniques for better accuracy.

