# Capstone-Project
1. Business Objective
Build a restaurant Success model for New York. I decided to create a model that can help restaurant lenders (such as banks) and investors decide whether they should lend/invest at a particular restaurant based on the likelihood that it is going to fail within the next few years.Once a customer approaches the bank with his business proposal my model can help the bank predict the star rating of the restaurant. If the rating is above 3.5 it is safe to invest or else the bank can ask the customer to make changes to his proposal and come back.
2. Data Ingestion
I have used Yelp API to get the all the restaurant per zip code in New York which had an off set of 1000 restaurants per zip.
To the same I have used the Google ApI to get more information on the Restaurants using the business ID per restaurant. Similar process has been followed to get the Review data too.
3. Visualizations: 
I have generated a carto map to see the restaurant density in new york based on the star rating.
https://parul29.carto.com/builder/c8e35596-9482-4a82-b02e-8cbb1e309212/embed
I used mat plotlib to generate more graphs to show my feature importance and also for the NLP part like word cloud.
4. Machine Learning: 
The project has used three machine learning models.  
Starting with different regressors like decision tree, random forest regressor, gradient boosting regressor, lasso regressor and got a r^2 value of .96.
To take care of the bias part I have used K-Fold cross validation and got very low error to validate my model further.
NLP has also been implememted and different visualization techniques and word cloud has been used for the same.
5. Deliverable: my model is going to predict the star rating once the bank enters the features of the new restaurant and based on the rating the bank can decide whether to give the loan or not.



