# CDEC_Data_Download

Summary: Function that downloads reservoir levels for major reservoir's in California from the California Data Exchange Center (CDEC). List of CDEC reservoir ID's can be found here: https://cdec.water.ca.gov/reportapp/javareports?name=ResInfo.

Inputs: CDEC reservoir ID (string), start date of data set [automatically pulls up to the most recent data] (integer), path location where csv will be stored (string).

Outputs: .csv file saved to specified path location.

Example: CDEC_scraping("NCM", 1991, "/Users/hunter/Desktop/Coding/Web Scraping/Nac_Data.csv")
