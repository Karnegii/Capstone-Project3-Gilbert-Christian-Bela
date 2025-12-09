# Capstone-Project3-Gilbert-Christian-Bela  

These files contain my machine learning project in which I was tasked to create a amachine learning model for a bank's marketing campaign.  
  
The main goal of the project would be to build and train a proper machine learning model that could predict whether a customer would subscribe to the marketed product, which is a term deposit, so that the bank could do their marketing more efficiently.  
  
The available features of each customer included in the dataset are the following :  
- age
- job
- balance
- housing
- loan
- contact (contact communication type)
- month (last contact month of the year)
- campaign (number of contacts performed during this campaign and for this client)
- pdays (number of days after the client was contacted from the previous campaign)
- poutcome (outcome of the previous marketing campaign)
- deposit (whether the customer deposits or not
  
Those were the variables initially included in the dataset. However, for the training purpose, I added a new variable :
- pcampaign (whether the customer was included in the previous campaign or not), which was extracted from pdays and poutcome  
  
The main model used is **Random Forest Model** with final F1 Score of **70.18%** after going through cross-validation benchmarking and further hyperparameter tuning.  
The model also shows balance and age as features with the highest importance in determining whether a customer would subsribe or not.
