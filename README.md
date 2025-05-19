This mini project is to showcase how machine learning/deep learning learn patterns from time series (also known as sequential) data.

**Project Description**: Stock prediction using deep learning model Long-short term memory (LSTM) and ML Models linear regressions and random forest.

**Feature Selected**: Adjusted Close, Highest price in a day, lowest price in a day, starting price of a day, 'RSI', 'EMA20', 'EMA100', 'EMA150'

**Target**: Price changes of a day (Adjusted Close - Open)

**Model Evaluation**: offset 5-7 units in price. Not ideal. Linear regression and random forest has better results (4 unit offset)

**Limitation**: Not ideal result. Less features that might impact to the price. The model is just depends on the historical price.
  - can add sentiment analysis as one of the input features (from social media)
  - can try binary classification (set target as up/down, define sigmoid activation function at the output layer 0,1)
  - can try with other machine learning model
  - this dataset is not friendly to use, can play other popular topic such as heart disease diagnosis, house price prediction, leaf disease classification (image) that have larger datasets and more features if interested. The public free dataset can be found in kaggle/ hugging face.
