# H2O Modelling Train Multiple Models for Each Level In Parallel

H2O is a distributed way of modelling , however if you want to train multiple H2O models in parallel , select the best model for each Product and generate elasticties for the best model, this code will  help achieve that goal 

This code is originally been written on Azure Databricks , so along with H2O Modelling , it has the below functionality :  

1. Set Up H2O Context & MLFlow in DataBricks
2. Runs various algorithms in H2O GRID parallely for each Product on Train Data
3. Selects the best model based on model selection criteria
4. Predict the test data using selected model
5. Save H2O Models in Databricks File System using MOJO
6. Obtain Model Coeffecients
7. Push H2OFrame to SQL Using Scala 

MLFlow is an efficient way on Databricks to track and secure the machine learnning training model runs by capturing a unique RUNID for every fresh notebook run 

The code has been written in Spark and H2O on Azure Databricks . Please view HTML file of Databricks code with results.  
Below is the link :   
https://priyal1508.github.io/priyal2203/H2O_Parallel_Modelling  

