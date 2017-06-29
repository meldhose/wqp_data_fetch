# wqp_data_fetch

Given a set of site IDs X that correspond to a single lake, a set of columns of interest Y, and a set of characteristics of interest Z, this script will query WQP to obtain data for all site IDs in X, then pull out only the columns in Y, then filter the rows based on the characteristics in Z. 

Example: This script retrieves data from https://www.waterqualitydata.us/portal/  (water quality portal) for Lake Mendota
