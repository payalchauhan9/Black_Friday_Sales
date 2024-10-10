**Black Friday Sales Prediction**

![Screenshot 2024-10-10 115607](https://github.com/user-attachments/assets/a5f2deff-93a8-456c-959b-a50ca7b65df5)

**Project Introduction**

Black Friday is an annual shopping event that occurs on the Friday after Thanksgiving in the United States, which is celebrated on the fourth thursday of November. It is known for its massive discounts and deals on a wide range of products, making it one of the busiest shopping days of the year. Retailers often offer significant price reductions to attract shoppers both online and in stores. Many stores offer highly promoted sales on Black Friday and open very early, such as at midnight, or may even even start their sales at some time on Thanksgiving. The major challenge for a Retail store or eCommerce business is to choose product price such that they get maximum profit at the end of the sales. Our project deals with determining the product prices based on the historical retail store sales data. After generating the predictions, our model will help the retail store to decide the price of the products to earn more profits. 

**Dataset Desscription**

The dataset is taken from kaggle. It contains features like Gender, Marital status, Age, Purchase amount, Category of products, City, etc. The dataset contains 12 columns and 550068 records. We are going to predict the purchase amount of the products.

**EDA**

Below are the observations which we have made from the data visualization done as part of the Data Understanding process.

  > For Age feature, we observed that the maximum purchase was done by consumers who belong to age group 26-35.

  > About 75% of the number of purchase is done by Male and the rest of the 25% is done by Female. From which we understand that Male consumers are the major contributor to the number of sales.

  > The city B is majorly responsible for the overall sales income, but when it comes to above product, it majorly purchased in the city C.

**Data Preparation**

  > Filled missing values in the Product_Category_2 and Product_Category_3.

  > Used LabelEncoder for encoding the categorical columns like Gender and City.

  > Applied random.randint to assign age randomly.

**Modeling Phase**

  > Splitted dataset into random train and test subset ratio 80:20.

  > Implemented multiple supervised models such as Decision Tree Regressor, Gradient Boosting Regressor.

**Conclusion**

Implanted multiple supervised models such as Decision Tree Regressor,Gradient Boosting Regressor
. Out of these supervised models, based on the MSE scores DecisionTreeRegressor was the best performer with a score of 3669.
