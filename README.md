# London-Bike-Share-By-using-LSTM
The dataset we'll be analyzing is the "Bike Share" data. It shows the amount of bikes rented every hour in London and it's related parameters.

### Aim
Our goal is to predict the number of future bike shares given the historical data of London bike shares

### Approach:
- Data
- Data preprocessing
- Exploratory Data Analysis
- Splitting the data into Train, Test
- Building Model
- Predicting Demand
- Evaluation

### Graph
![image](https://user-images.githubusercontent.com/86415241/139055797-f3308d99-0ab8-42bc-8e41-225b2e55b819.png)

![image](https://user-images.githubusercontent.com/86415241/139055836-071bd9b7-98ec-4215-b92e-68d2888e7c8b.png)


Please keep in mind that our model can only predict one point in the future. Having said that, it is performing wonderfully. Our model does a fair job of predicting (understanding) the overall pattern, even though it can't really capture the extreme values.


### Conclusion:
We simply preprocessed a real dataset and used it to forecast bike-sharing demand. We trained the model using subsequences from the original dataset using a Bidirectional LSTM model. We even obtained some great results
