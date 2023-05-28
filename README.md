# Car_Sales_prediction
Car sales prediction using ANNs
### We came across the problem where...
You are working as a car salesman and you would like to develop a model to predict the total dollar amount that customers are willing to pay given the following attributes: 
- Customer Name
- Customer e-mail
- Country
- Gender
- Age
- Annual Salary 
- Credit Card Debt 
- Net Worth 
### We create-
The model should predict: 
- Car Purchase Amount 


![car](https://github.com/Atharva1702/Car_Sales_prediction/assets/90234696/9ce7c33e-6c99-4093-97c4-eae96657118b)



We cleaned the data and removed the unwanted column such as names, customer email, and the country as
these factors won't affect our model and can create more complexity.
We did some visualization we regards to the car purchase amount and other parameters to get a better understanding of the dataset.


![eec15baf-54f6-4f94-ba4b-df7232c98b4d](https://github.com/Atharva1702/Car_Sales_prediction/assets/90234696/1d70011e-da24-46a8-8e3a-ca9a73c75228)


ANNs are the information processing models inspired by the human brian.

We can teach ANN to do the task.
There are some steps in ANN:
#### Step 1 - Forward propagation

#### Step 2 - Error calculation

#### Step 3 - Back propagation

#### Step 4 - Weight update

We do this over and over again, everytime we update the weight it is called **EPOCH**.


![image](https://github.com/Atharva1702/Car_Sales_prediction/assets/90234696/8165ffb1-bdee-4dda-8742-c1b92ad0bd8e)

We created an Artificial neural network with the help of Keras and trained it over 100 epochs to make it learn effectively. More the epochs the better hte machine will learn.

model = Sequential()

model.add(Dense(40,input_dim = 5 ,activation = 'relu'))

model.add(Dense(40,activation = 'relu'))

model.add(Dense(1,activation = 'linear'))

this is the ANN that we created.

#### So, now whenever the costumer comes to the car dealer showroom this model based on his information can show the price range in which he may buy and that can help the dealer to show the car in that particular range not much cheap or expensive.
