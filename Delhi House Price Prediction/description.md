# Delhi House Price Prediction

![](https://m.economictimes.com/thumb/height-450,width-600,imgsize-201544,msid-80555468/1.jpg)

## Project Overview
The "Delhi House Price Prediction" project focuses on forecasting house prices in different localities of Delhi. The goal is to build a predictive model that estimates house prices based on key features like area, number of bedrooms, and locality. Using a dataset from Kaggle, the project explores how various attributes influence housing costs, offering valuable insights for both buyers and sellers in the real estate market.

## Data Dictionary
The dataset contains 1259 rows and 11 columns, each representing specific house attributes:


| Column Name  | Description                          |
|--------------|--------------------------------------|
| Area         | Area of the house in square feet    |
| BHK          | Number of bedrooms                  |
| Bathroom     | Number of bathrooms                 |
| Furnishing   | Furnishing status                   |
| Locality     | Locality of the house               |
| Parking      | Number of parking spaces available  |
| Price        | Price of the house in INR           |
| Status       | Property's status (ready to move or under construction) |
| Transaction  | New property or resale              |
| Type         | Type of the property                |
| Per_Sqft     | Price per square foot               |

## Impact
The project serves two key purposes:

1. **For Buyers and Sellers:**
   - Buyers can make well-informed decisions by understanding market trends and estimated prices.
   - Sellers can determine fair pricing strategies based on market insights.

2. **Data Insights and Model Performance:**
   - **Exploratory Data Analysis (EDA):** Factors like area, bedrooms, and locality strongly affect prices. High-end areas such as Punjabi Bagh, Lajpat Nagar, and Vasant Kunj command premium rates. The preference for builder floor properties highlights buyers' demand for customization and independence.
   
   - **Model Accuracy:** The project employed regression models, including Decision Tree Regressor and Random Forest Regressor. The Random Forest Regressor achieved the highest accuracy at 84.98%, outperforming the Decision Tree model.

## Conclusion
The "Delhi House Price Prediction" project provides a reliable tool for estimating house prices in Delhi's competitive real estate market. By leveraging advanced regression models, it delivers accurate predictions, enabling better decision-making for both buyers and sellers.

