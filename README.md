# DSA 210 Term Project: Car Price Prediction 

## Project Overview  
This project aims to predict the price of Mercedes and Honda vehicles based on various factors such as model, year, mileage, fuel type, transmission, and more. By applying data science techniques, I will analyze how these attributes influence the value of cars.  

## **Motivation**
# Car Price Prediction - Mercedes & Honda

## Motivation

- **Personal Interest**
  
  I have a personal interest in analyzing cars that are for sale and I am particularly interested in Honda and Mercedes vehicles. Exploring car pricing patterns and factors influencing prices is a fascinating real-world problem.
- **Application**
  
  I want to integrate this personal interest into my work in data science and this project allows me to apply machine learning techniques to a practical scenario.



## Data Source

This project uses two datasets from Kaggle:
- **Mercedes Used Car Listing** ([Dataset Link](https://www.kaggle.com/datasets/mysarahmadbhat/mercedes-used-car-listing))
- **Honda Cars Data** ([Dataset Link](https://www.kaggle.com/datasets/omartorres25/honda-data))

The Mercedes dataset contains information about various Mercedes cars, including price, transmission type, mileage, fuel type, road tax, MPG, and engine size. The Honda dataset is scraped from cars.com and includes details like model, condition, price, ratings, drivetrain, and transmission.

## Data Analysis

- **Data Cleaning & Preprocessing:** Handle missing values, convert categorical variables, and normalize numerical values.
- **Exploratory Data Analysis (EDA):** Visualizing price distribution, correlation analysis between features.
- **Feature Engineering:** Creating new relevant features that could help improve predictions.
- **Machine Learning Models:** Applying regression techniques to predict car prices based on various attributes.
- **Evaluation:** Using RMSE, MAE, and R-squared to evaluate model performance.

## Findings

- Identification of key factors that influence car prices.
- Differences in pricing trends between Mercedes and Honda vehicles.
- Potential insights for buyers and sellers regarding market trends.

## Limitations and Future Work

- The dataset may not include real-time data, leading to outdated price trends.
- The model can be further improved with more diverse datasets, including cars from other brands.
- Future iterations could integrate real-time web scraping for dynamic price predictions.

## How to Run

1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook or script to process the data and train the model.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Contributing

Feel free to fork this repository, open issues, or submit pull requests!

## Data Source
The data that will be used in this project comes from publicly available datasets on Kaggle.
1. **Mercedes Used Car Listing**: Contains data on used Mercedes cars, including price, transmission, mileage, fuel type, road tax, miles per gallon (mpg), and engine size.
   - [Dataset Link](https://www.kaggle.com/datasets/mysarahmadbhat/mercedes-used-car-listing)

2. **Honda Cars Data**: Contains data on Honda vehicles such as model, condition, price, ratings, transmission, and more.
   - [Dataset Link](https://www.kaggle.com/datasets/omartorres25/honda-data)

## Data Analysis
The project follows a structured approach:
1. **Data Cleaning & Preprocessing**: Handling missing values, standardizing formats, and removing irrelevant columns.
2. **Exploratory Data Analysis (EDA)**: Visualizing relationships between variables to understand pricing trends.
3. **Machine Learning Models**: Implementing Machine Learning Models to predict car prices.

## Expected Findings
- Key factors affecting price might include mileage, fuel type, and engine size.
- Different brands may have different depreciation trends based on model popularity and market demand.

## Limitations and Future Work
- The datasets may not include all factors influencing car prices, such as accident history or region-specific demand.
- Future work could include integrating more brands and economic indicators, such as inflation and fuel price trends.
- The model could be further refined using deep learning techniques for better accuracy.

