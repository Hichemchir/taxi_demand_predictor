# Taxi demand predictor service

This directory contains all the code needed to solve a real business problem, to match the supply of Taxis in New York with user demand. 

My job is to help the operations team keep the fleet as busy as possible. We want to avoid an excess of drivers and a shortage of customers. 
We can't control the number of drivers, but we can predict how many users will be available to meet demand. 

Data taken from the following site : https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

I'll first extract the raw data, filter it to get validated data, transform it into Times Series data and finally transform it into features and target to be able to set up ML models.
