###  Time Series Forecasting on Grouped Dataframe ### 

Objective  :  If you have to train multiple Time Series Models on each Product_ID level, select the best model on Evaluation Metric, and forecast for future ,
without compromising on the computation time  , this code is a good starting point

This code has the following functionalities  :  

1. Sets up ML Flow Tracking  
2. Load Dummy data through DBFS 
3. Time series function - which trains multiple classical TS models , computes evaluation metric and forecasts variables into the future 
4. Call the function on Grouped Dataframe based on Gapply  
5. Save the forecasts onto DBFS path  
6. Save the ML flow RUN


All the above code has been implemented in Azure Databricks ,hence please find the below link  to have a look at the output results : 

https://priyal1508.github.io/priyal2203/Time_Series_Forecast_GapplySpark
