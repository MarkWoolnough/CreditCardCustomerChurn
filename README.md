# CreditCardCustomerChurn
Project artefacts for Watson Studio.

I've included 2 data sets to work with:  CUST_SUM.csv and CHURN_RATE.csv.

Q:  What can you do with CUST_SUM.csv in Watson Studio:

A:  All of this:
1.  Create a project, upload the data asset.
2.  Create a Watson ML service for your project.
3.  Use Watson Machine Learning to create a binary classification model using different techniques, with point and click.
4.  Deploy and test the model created above using the test tab in the deployed service.
5.  Create a new Model Flow (SPSS flow) from file and explore the data asset using the .str file included in this repository.  Steps include data analysis, filtering, setting the data types (target), building a C5.0 model, analysing the model and a toy example of creating an unsupervised learning model using K-means (doesn't work very well, but shows the art of the possible).

Q:  What can you do with CUST_SUM.csv and CHURN_RATE.csv?

A:  There's a Jupyter notebook that can be provisioned for data analysis using Brunel visualisations (very cool!).
