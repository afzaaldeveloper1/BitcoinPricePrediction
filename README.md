# BitcoinPricePrediction

This Project is about using different RNN algorithms to make Bitcoin Price Predictions. Jupyter Notebook was used in an AWS Sagemaker Notebook instance.
Two different RNN architecture were implemented and analyzed. The first one was a 2 layer LSTM using PyTorch. The second was AWS Sagemaker's DeepAR algorithm. 
The Jupyter notebooks/code that has "Final Capstone" in its commit are the 2 notebooks that show the full code implmementation of these RNN structure.
The data used for making these predictions was obtained from Kaggle and is called bitstampUSD_1-min_data_2012-01-01_to_2020-04-22.csv and can be found at 
https://www.kaggle.com/mczielinski/bitcoin-historical-data
It is a csv file and both notebooks read that csv file and make some processing in order to run the algorithm. Please make sure that one creates a folder called "data" and place this csv file there so that if one were to run the Jupyter notebook exactly as it is, no errors are created.

