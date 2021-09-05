Flight Fare Prediction software using Machine Learning Python Flask.


*Problem Statement*: In the modern world,travelling through flights has become an major part of today's lifestyle as most of the people don't want to waste their time on travelling so they opting flight even for short distance instead of train or bus.he flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season.Therefore this Project will help the ones who are planning for trip to save money and time.

*Approach Used* 

The main goal is to predict the fares of the flights based on different factors available in the dataset.

1.Data Exploration : I started exploring dataset using pandas,numpy,matplotlib and seaborn.

2.Data visualization : Ploted graphs to get insights about dependend and independed variables.

3.Feature Engineering : Removed missing values and created new features as per insights.

4.Model Selection I : 1. Tested all base models to check the base accuracy. 2. Also ploted residual plot to check whether a model is a good fit or not.

5.Model Selection II : Performed Hyperparameter tuning using gridsearchCV and randomizedSearchCV.

6.Pickle File : Selected model as per best accuracy and created pickle file using joblib .

7.Webpage & deployment : Created a webform that takes all the necessary inputs from user and shows output. After that I have deployed project on heroku and Microsoft Azure

## User Interface of Website 


*Main Page*

![Screenshot (372)](https://user-images.githubusercontent.com/88200767/132125607-5331d3d3-bfdc-4a72-905b-ba168a7cb9d6.png)


![Screenshot (373)](https://user-images.githubusercontent.com/88200767/132125630-dd49178e-b88c-451c-a222-438167f3ae28.png)



*Main Page with filled information*

![Screenshot (374)](https://user-images.githubusercontent.com/88200767/132125636-47a2d931-9010-4a43-a2d4-de8fe10c88d2.png)



*Main Page After Predicting average Flight Fare*

![Screenshot (375)](https://user-images.githubusercontent.com/88200767/132125650-8421b779-f66f-4ec0-a734-a9dce61da949.png)



*Data in Database*

![Screenshot (376)](https://user-images.githubusercontent.com/88200767/132125652-1d3a5291-ea3c-49c7-bf4a-e1b7094a2c8a.png)

