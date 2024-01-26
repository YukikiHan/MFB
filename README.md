# MFB
MFB: A Generalized Multimodal Fusion Approach for Bitcoin Price Prediction Using Time-Lagged Sentiment and Indicator Features
# Environment
Install Python IDE, PyCharm from here
 https://www.jetbrains.com/pycharm/download/?section=windows
# Datasets
- Tweets: https://www.kaggle.com/datasets/hiraddolatzadeh/bitcoin-tweets-2021-2022 
- News: https://figshare.com/articles/dataset/MarketData_for_MarketPredict_RESTFul_API_including_News_and_Market_Data/14754966 
- Bitcoin price: https://coinmarketcap.com/
# Experiment steps
- **Data Collection**: Gather Bitcoin price, financial tweets and news data.
- **Preprocessing**: Apply various the preprocess techniques for structured data and apply VADER to extract sentiment scores.
- **Lagged Data Correlation**: Correlate sentiment scores with Bitcoin price to identify temporal relationships.
- **Fusion Model**: Process the data through a sequence of layers within the model, including embedding, recurrent with attention, and dense layers.
- **Feature Optimization**: Utilize correlation matrix filtering, BorutaShap feature selection, and SPB optimization to refine model features.
- **Model Training**: Compile and train the model, tuning it to optimize performance.
- **Performance Evaluation**: Assess the model's effectiveness using various metrics such as recall, precision, F1 score, and accuracy.
- **Bitcoin Price Forecasting**: Deploy the trained model to predict the next hour's Bitcoin price, with outcomes evaluated against metrics like MAE, MSE, R², RMSE, and MAPE.

