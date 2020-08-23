# Forecast

The forecast has been implemented usinf SARIMA model. The forecast shows steep descent which is different from the real picture. In reality around the first week of August, there was a sudden surge in number of tests, and thus, the increase in number of cases. 
I have used SARIMA model in an order of (3,0,1) thus, I have only used auto-regression and moving average for predicting. The order for SARIMA (AR,MA) was retrieved from acf and pacf model, and the data happen to be stationary, thus, no differenciating was needed
