# Used Bikes Data Analysis (EDA)

## Project Overview
This project involves the exploration and analysis of used bike data scraped from the *Bike Dekho* website. The primary goal was to clean, preprocess, and analyze the data to generate valuable insights about used bikes based on various features like location, brand, year, kilometers, price, users, and vehicle type.

## Tools and Technologies
- **Python**
- **Libraries Used**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Selenium
  - Scikit-learn

## Data Collection
- The data was scraped using **Selenium** from the *Bike Dekho* website, focusing on various cities.
- The dataset consists of 7 columns: `Location`, `Brand_name`, `Year`, `Kilometers`, `Price`, `Users`, `Vehicle_type`.
- The final dataset contains **966 rows** and **7 columns**.

## Data Preprocessing
1. **Handling Null Values**:
   - Null values were handled by replacing them with the mean, median, or mode using the `fillna()` function.
   
2. **Handling Outliers**:
   - Outliers were identified using **scatter plots**, **KDE plots**, and **box plots**.
   - Outliers were treated using the **capping method**.

3. **Final Cleaned Dataset**:
   - After preprocessing, the final dataset was validated and cleaned for analysis.

## Exploratory Data Analysis (EDA)

### Univariate Analysis Insights
1. **Kilometers**:
   - Minimum kilometers: 1,000 to 84,000
   - Average kilometers: ~50,000
   - Majority of bikes have approximately 20,000 kilometers.

2. **Price**:
   - Minimum price: 8,000
   - Maximum price: 175,000
   - Average price: 60,000
   - Right skew of 0.8 in the price distribution.
   - Majority of bikes are priced between 25,000 and 75,000.

3. **Location**:
   - Most vehicles are from Bangalore (0-370 vehicles).
   - Least vehicles are from Ahmedabad (0-80 vehicles).

4. **Brand Name**:
   - Royal Enfield is the most common brand.
   - Bajaj is the most frequent company in the dataset.

5. **Year**:
   - Most bikes are from the years 2015 to 2019.

6. **Users**:
   - 93% of bikes are owned by the first owner.
   - Only 7% are owned by second owners.

### Bivariate Analysis Insights
1. As the number of kilometers increases, the price decreases.
2. As the year of the bike increases, the number of kilometers driven decreases.
3. Older bikes tend to have fewer users.
4. Bike prices increase with the year of manufacture.
5. **Price difference**: Petrol vehicles are more expensive than electric vehicles.
6. Revenue generation is highest in Bangalore and Hyderabad.
7. Bike prices are lower in Ahmedabad and Jaipur.
8. Royal Enfield bikes tend to have higher prices across all cities.

## Conclusion
This analysis provides valuable insights into the used bike market, highlighting trends related to kilometers driven, pricing, bike brand popularity, and geographical differences in bike prices. The insights can help buyers and sellers make more informed decisions in the used bike market.







