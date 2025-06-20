# ETL_Project
## Data ETL Pipeline of Bitcoin Historical Data(2012-2025)
### Summary:
This ETL Pipeline extracts Bitcoin data(2012 - 2025) from CSV, executed data cleaning and transformation, and is loaded into a MongoDB Atlas cloud databse.

#### Steps Taken:

- **Extract** CSV data (Bitcoin historical OHLCV)
- **Transform** data: clean, fill missing, engineer new columns (moving average, % change, day_of_week, hour_of_day)
- **Load** data into MongoDB Atlas

#### Technology Used:

- Python 3
- Pandas
- MongoDB Atlas (cloud)
- Google Colab

#### How to Run:

1. Clone this repo
2. Open the notebook in Google Colab
3. Set your MongoDB Atlas connection string
4. Run the ETL pipeline

#### Original Data File:
The original dataset was downloaded from Kaggle which can be found on the link below!
- [Click Me](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data/data)
