# Python-JupyterNotebook-Stock

This project focuses on analyzing historical stock data for Tata Power (TATAPOWER.NS) spanning from 2013 to 2021, with the goal of predicting future price movements.
Key features of this project:

Automated data collection from Yahoo Finance
Statistical analysis of stock price trends
Machine learning model for price predictions
Data visualization to identify patterns and trends

Stock market prediction has always fascinated me as it combines financial knowledge with data science techniques. This project demonstrates how Python's powerful libraries can be leveraged to analyze market data and make informed predictions.

Data Acquisition & Processing:

Used pandas_datareader to fetch 8 years of Tata Power stock data from Yahoo Finance API
Organized data into a structured DataFrame with high, low, open, close, volume metrics
Exported raw data to CSV for persistence and reusability
![Screenshot 2025-04-04 013745](https://github.com/user-attachments/assets/201ebe22-1a10-4277-a931-faaa0a7366ca)


Model Development:

Selected RandomForestRegressor from scikit-learn for its ensemble learning capabilities
Split data into 80% training and 20% testing sets
Trained model using historical date values to predict price vectors
Achieved 70.75% prediction accuracy (R² score) on test data

Visualization:

Created scatter plots showing relationship between opening and closing prices
Developed time series visualization of closing price history
Used matplotlib for all visualizations with custom formatting
![Screenshot 2025-04-04 014029](https://github.com/user-attachments/assets/b92484ef-86c0-4687-8e31-444e23bbed0a)

Key Technical Challenges:

Converting date formats for machine learning compatibility
Feature selection for optimal prediction accuracy
Balancing model complexity with performance

This project demonstrates practical application of data science in financial markets.
