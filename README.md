# wqp_data_fetch

Given a set of site IDs X that correspond to a single lake, a set of columns of interest Y, and a set of characteristics of interest Z, this script will query WQP to obtain data for all site IDs in X, then pull out only the columns in Y, then filter the rows based on the characteristics in Z.

Example of data retrieval:
As an example, this script retrieves data from https://www.waterqualitydata.us/portal/  (water quality portal) for Lake Mendota.
The data obtained for Lake Mendota is available in data/lake_mendota_data.csv

