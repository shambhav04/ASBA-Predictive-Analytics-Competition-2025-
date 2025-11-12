# Airbnb Price Prediction — ASBA Predictive Analytics Competition (2025)

This project was completed as part of the BUSA3020 Advanced Analytics Techniques unit at Macquarie University.  
It was conducted for the ASBA Predictive Analytics Competition (2025) on Kaggle, where participants were tasked with predicting Airbnb listing prices across Melbourne using Python.


### Problem Statement
The goal was to predict nightly Airbnb prices in Melbourne using available host, property, and location data.  
The project demonstrates how data analytics and machine learning can help property hosts and managers make informed pricing decisions based on the key factors that influence price.


### Approach
The workflow was divided into three main stages:

1. **Data Cleaning and Preparation**  
   - Handled missing values, converted incorrect data types, and removed irrelevant fields.  
   - Normalised inconsistent entries and limited categorical variables to the top five categories for better model interpretability.

2. **Feature Engineering**  
   - Created new variables such as:  
     - `amenities_count`  
     - `availability_ratio`
     - `Time_as_a_Host`  
     - `days_since_last_review`  
     - `superhost_flag`  
     - `neighbourhood_review_density`  
   - These features captured host experience, listing quality, and demand patterns.

3. **Model Building and Evaluation**  
   - Implemented and compared multiple regression models:  
     - Gradient Boosting Regressor  
     - Lasso Regression  
     - Support Vector Regression (SVR)  
   - Evaluated performance using Mean Absolute Error (MAE) and visualised model results.

### Output
- The final model predicted nightly listing prices (AUD) for 3,000 unseen Airbnb listings.  
- Outputs included cleaned datasets, correlation heatmaps, and a CSV file containing price predictions for Kaggle submission.  
- The team, "Back Benchers," placed 26th out of 106 teams, competing with both Bachelor and Master of Business Analytics students, including several industry professionals.

### Value to Stakeholders
This project provided insights and a reproducible workflow for:
- Hosts to identify the key factors influencing price and optimise their listings.  
- Property managers to benchmark and adjust rates based on property and location attributes.  
- Investors to analyse neighbourhood performance and forecast potential returns.  

The model pipeline can be reused or adapted for other cities or property markets.

### Potential Use Cases
- Rental yield forecasting for real estate agencies  
- Price benchmarking for hotels and short-stay platforms  
- Tourism analytics and neighbourhood trend detection  

### Reflection
This competition offered practical experience with real-world data challenges such as missing information, skewed distributions, and model tuning.  
It showed me that getting the basics right, like clean data, thoughtful features, and clear logic, matters more than using the most complicated models.

### Tools and Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter  

### Repository Contents
- `Airbnb_Pricing.ipynb` — Main notebook (data cleaning, feature engineering, modelling, and evaluation)  
- `BUSA3020_Back_Benchersbest.csv` — Final Kaggle predictions  
- `README.md` — Project summary and documentation  

### Links
- [Competition Page on Kaggle](https://www.kaggle.com/competitions/asba-predictive-analytics-competition)  
- [LinkedIn Post](<add-your-link-here-once-posted>)  

### Citation
This project was completed as part of the BUSA3020 Advanced Analytics Techniques unit at Macquarie University using a dataset provided through the ASBA Predictive Analytics Competition (2025).  

Milunovich, G. (2025). *ASBA Predictive Analytics Competition (2025): Predicting Airbnb Listing Prices in Melbourne, Australia*. Kaggle.  
Retrieved from [https://www.kaggle.com/competitions/asba-predictive-analytics-competition](https://www.kaggle.com/competitions/asba-predictive-analytics-competition)
