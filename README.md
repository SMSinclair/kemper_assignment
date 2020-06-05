Data set and Analysis Test


This test should take no longer than half a day to complete.
Attached with this document are 4 data sources:

1. CLAIM_COUNT_DATA_SET
2. CLAIM_VEHICLE_DATA_SET
3. CLAIM_CLAIMANT_VEHICLE_SET
4. CLAIM_POLICY_DATA_SET

The first part of the test is to bring the datasets together into one file for analysis. 
As part of this test you will need to answer the following questions:

1. How many records are in the clean final data set? 
- There are 35250 records in the clean final data set.
2. What trends, information or observations are you able to find and present about the data?
- There are very few claims involving vehicles manufactured in 2011.
- There are very few cases where the insured reports a theft claim and many more where the claimant reports (approximately 2 percent vs. 40 percent)
3. With Nonstandard Insurance we see claims that are reported with drivers not listed on our policies, referred to as unlisted drivers in the data set. If we had a 1994 vehicle what percent of reported claims with unlisted drivers would we expect to have.
- If we had a 1994 vehicle, we would expect to have ~22.45% of reported claims with unlisted drivers.
- See the linear regression below for further explanation. Vehicle year explains ~92% of the variance in the percentage of claims with an unlisted driver.