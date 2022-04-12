# Prediction-of-Online-Shoppers-Purchasing-Intentions
The main objective of the study is to better understand how and if online browsing data can be used with machine learning to improve and enhance the ability to predict online consumer habits, and whether a customer is likely to make a purchase.  The main hypothesis statement for the project is as follows:
 **“The likelihood of an online shopper making a purchase can be predicted using online browsing data and machine learning”**

The data consists of 18 attributes belonging to 12,330 entries with target variable “Revenue”, each entry represents a session of a different user in a 1-year time period. The data can be found in the link below. The data definition is also available on the page. 
https://www.kaggle.com/roshansharma/online-shoppers-intention
During the data exploratory analysis, we noticed that we found 14 null records,  we created dummy variables, filled the null variables with medians and scaled the discrete variables using a pipeline. The data has been split pre-pipeline into training and test data. Since  the discrete data are skewed  and the target variable ‘Revenue’ is imbalanced, the data has also been stratified by the target variable.  To proceed with the correlation matrix between pairwise correlation of all features with target variable “Revenue”, we observed “Page Value” is highly positively correlated with “Revenue”.

**CONCLUSION**:
With evaluating multiple classification models performance, we are able to predict the likelihood of online shoppers making a purchase by developing a machine learning model. Random Forest model is the best classifier among tested models  to predict the purchase intentions of online shoppers. All the models  that we used for this specific dataset would benefit more if we would add more training instances to them.
Our observations indicate that on weekdays customers are most inclined to buy from  websites, also, winter and spring are the busiest seasons, customers overall have more intention to online shopping, during the purchase process, most customers are more often made a buy decision in a short duration, especially for new customers. It might show marketers could enhance products accordingly to increase the satisfaction. 

