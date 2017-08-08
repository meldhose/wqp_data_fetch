# wqp_data_fetch

WQP Data Retrieval (wqp_data_fetch) provides an easy way to obtain data points corresponding to a lake from the water quality data portal (https://www.waterqualitydata.us/portal/). 
Given a set of site IDs X that correspond to a single lake, a set of columns of interest Y, and a set of characteristics of interest Z, this script will query WQP (water quality portal) to obtain data for all site IDs in X, then pull out only the columns in Y, then filter the rows based on the characteristics in Z. This will produce a pandas DataFrame containing the data points.

Example of data retrieval:
As an example, this script retrieves data for Lake Mendota from https://www.waterqualitydata.us/portal/  (water quality portal).
The data obtained for Lake Mendota is available in data/lake_mendota_data.csv

