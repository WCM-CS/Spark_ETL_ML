# Spark_ETL_ML

This project uses the spark engine to process and train a linear regression model. The code includes a simple ETL transforming a CSV by excuding null and duplicate values, loads to a parquet file. Then the parquet file is used to train the model. Data is split 70/30 from training and testing data to evaluate the models accuracy via MSE MAE and r^2.
