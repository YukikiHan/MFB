# MFB
MFB: A Generalized Multimodal Fusion Approach for Bitcoin Price Prediction Using Time-Lagged Sentiment and Indicator Features
# Environment
Install Python IDE, PyCharm from here:

https://www.jetbrains.com/pycharm/download/?section=windows
# Datasets
- Tweets: https://www.kaggle.com/datasets/hiraddolatzadeh/bitcoin-tweets-2021-2022 
- News: https://figshare.com/articles/dataset/MarketData_for_MarketPredict_RESTFul_API_including_News_and_Market_Data/14754966 
- Bitcoin price: https://coinmarketcap.com/
# Experiment steps
- **Data Collection:** Download Bitcoin price, financial tweets and news data respectively from the links given above.
- **Preprocessing:** `run Data Standardization.ipynb`, preprocesses the collected data to obtain structured data.
- **Lagged Data Correlation:** `run Correlation Analysis.ipynb`, firstly applies VADER to extract sentiment scores and then correlates the results with Bitcoin price to identify temporal relationships.
- **Feature Optimization:** `run Data Standardization.ipynb`, uses a combination of multiple methods to optimize features.
- **Model Training and Performance Evaluation:** `run Split_data.ipynb`, divides the test and training set; `run MFB and baseline on news.ipynb` and `run MFB and baseline on tweets.ipynb`, applies performance metrics to compare the effectiveness of MFB and baseline models on news and tweets.
- **Bitcoin Price Forecasting:** `run MFB Optimizer Comparison.ipynb` and `run MFB Price Prediction on Bitcoin.ipynb`, optimizes and deploys the trained model to predict Bitcoin for the next hour, and compares the results with other related methods.
# License
EDS is licensed under the GNU General Public License; for more information, read the LICENSE file or refer to:

http://www.gnu.org/licenses/
# Citation
A related paper is submitted to the SCI journal.
