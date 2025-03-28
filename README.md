Objective

In this project, the objective is to predict the Car Selling Price based on various features like Car's Present_Price, Kms_Driven, Owner, Fuel_Type, Seller_Type, and Transmission. We will use the CAR DEKHO dataset from Kaggle. This dataset contains information about used cars listed on Car Dekho.


We can predict the Car Selling Price by filling in the data on the UI, after which the prediction will be displayed on the UI.

Dataset Preview

A preview of the top five rows of the Car dataset:

| | Car_Name | Year | Selling_Price (lakhs) | Present_Price (lakhs) | Kms_Driven | Fuel_Type | Seller_Type | Transmission | Owner |
|-| -------- | ---- | ------------- | ------------- | ---------- | --------- | ----------- | ------------ | ----- |
|0|     ritz | 2014 |	       3.35 |          5.59 |	   27000 |	  Petrol |	    Dealer |       Manual |     0 |
|1|      sx4 | 2013 |          4.75 |	       9.54 |	   43000 |    Diesel |	    Dealer |	   Manual |	    0 |
|2| 	ciaz | 2017	|          7.25 |          9.85	|       6900 |	  Petrol |  	Dealer |	   Manual |	    0 |
|3|  wagon r | 2011 |	       2.85 |	       4.15	|       5200 |	  Petrol |	    Dealer |	   Manual |	    0 |
|4|    swift | 2014 |          4.60	|          6.87	|      42450 |    Diesel |   	Dealer |       Manual |	    0 |

Description of variables in the dataset

Car_Name: Name of the car sold

Year: Year the car was bought

Selling_Price: Price at which the car was sold

Present_Price: Price of the same car model in the current year

Kms_Driven: Number of kilometers the car was driven before it was sold

Fuel_Type: Type of fuel the car uses

Seller_Type: Type of seller

Transmission: Gear transmission of the car (Automatic / Manual)

Owner: Number of previous owners


Car Price Prediction directory tree

```
├─ Templates
│  └─ index.html
│
├─ app.py
││
├─ rf_regression_model.pkl
│  
├─ Car Price Prediction.ipynb
│
├─ LICENSE
│  
├─ car data.csv
│
├─ Procfile
│
├─ README.md 
│
└─ requirements.txt
    
```
    
```Templates``` : contains templates for UI

```app.py``` : Front and back end portion of the web application

```Car Price Prediction.ipynb``` : conatains ipynb file (Jypiter Notebook file)

```rf_regression_model.pkl```  : contains model for prediction

```requirements.txt``` : required libraries 

```car data.csv```  : conatins raw data as csv file

Installation

* Clone this repository and unzip it.

* create new env with python 3 and activate it .

* Install the required packages using pip install -r requirements.txt

* Execute the command: python app.py

* Open ```http://127.0.0.1:5000/``` in your browser.

