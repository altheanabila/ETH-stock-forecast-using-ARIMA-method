# Ethereum-forecast-using-ARIMA-method

I try to forecast the stock price of Microsoft using ARIMA method. The data is downloaded in range of period 3 years. By using Python libraries namely pandas, numpy and pmdarima, we could see the result through line graphs.
On the data processing, we use adjusted closing price in order to run ARIMA method.

1. Download the data of stock
[ETH](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH.csv)

2. Import the data into panda
![TestImage1](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH1.png)
![TestImage1](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH2.png)

3. Processing the lag features
![TestImage1](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH3.png)


4. Define Data column, index features, training data and test data (must be less)
![TestImage1](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH4.png)

5. Define test data

![TestImage1](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH5.png)

6. import pmdarima,and find the best fit of model 

![TestImage1](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH6.png)


7. Run the forecast model to predict stock price

![TestImage1](https://github.com/altheanabila/Ethereum-forecast-using-ARIMA-method/blob/main/ETH7.png)
