# Natural Language Processing Stock Predictor
The purpose of this project is to see if a company's online presence (articles) can affect its stock prices. In this project, I focus on 5 major tech companies: Google, Facebook, Amazon, Microsoft, and Apple

3 jupyter notebooks for this analysis:
-
1) [Initial Analysis](https://github.com/anguslin/NLP-Stock-Predictor/blob/master/Initial-Stock-Analysis-Research.ipynb)
- This notebook contains the initial analysis of the stock data, determining which features to engineer and include as part of training data.
2) [Stock Data Scraping](https://github.com/anguslin/NLP-Stock-Predictor/blob/master/companies/Scrape-Companies-Stock-Data.ipynb)
- This notebook contains the scraping of past stock data from Google Finance API and data cleaning.
3) [Article Scraping and Final Model](https://github.com/anguslin/NLP-Stock-Predictor/blob/master/companies/Data-Preparation-and-LSTM-Model.ipynb)
- This notebook contains web scraping for each of the companies, word embedding for the articles, separating training and testing data, and the final LSTM model built with Keras.
