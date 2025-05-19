This mini project is to showcase how machine learning/deep learning learn patterns from time series (also known as sequential) data.

**Project Description**: Stock prediction using deep learning model Long-short term memory (LSTM) and ML Models linear regressions and random forest.

**Feature Selected**: 
  - Adj Close: Adjusted closing price based on dividens and stock-split 
  - High: Highest price in a day
  - Low: Lowest price in a day
  - Open: First trade's price of a day
  - Relative Strength Index (RSI)
  - Exponential Moving Average 20 days (EMA20): Short-term trend
  - Exponential Moving Average 100 days (EMA100): Mid-term trend
  - Exponential Moving Average 150 days (EMA150): Long-term trend

**Target**: Price changes of a day (Adjusted Close - Open)

**Model Evaluation**: offset 5-7 units in price. Not ideal. Linear regression and random forest has better results (4 unit offset)

**Limitation**: Not ideal result. Less features that might impact to the price. The model is just depends on the historical price.
  - can add sentiment analysis as one of the input features (from social media)
  - can try binary classification (set target as up/down, define sigmoid activation function at the output layer 0,1)
  - can try with other machine learning model
  - this dataset is not friendly to use, can play other popular topic such as heart disease diagnosis, house price prediction, leaf disease classification (image) that have larger datasets and more features if interested. The public free dataset can be found in kaggle/ hugging face.
