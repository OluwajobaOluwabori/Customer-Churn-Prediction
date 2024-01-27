# Customer-Churn-Prediction with PySpark
In every B2C business, there will always be instances when users stop using your service or app. This is known as churn, and it is very crucial to identify which users are at risk of churn. By accurately identifying these users before they leave and offering them discounts and incentives, companies can potentially save millions in revenue. Predicting churn rates is a critical task for data scientists and analysts who work in such customer-facing businesses. By analyzing data, potential churn risks can be identified and proactive measures can be taken to prevent it.
## Project Motivation
The goal of this project is to accurately predict users capable of churning. The full dataset is 12GB, due to its size this could not be done locally, so an Elastic MapReduce (EMR) cluster was deployed to perform tasks in the AWS cloud and I will analyze a mini subset in the workspace.
## Libraries
Apache Spark 3.3.24 with hadoop 3.0, Java 8 and Findspark were used in this project. Findspark was used in order to locate the spark in the system.
NumPy
Pandas
Seaborn
Matplotlib
PySpark 
These references were helpful in setting up spark on Google Colab and jupyter notebook [Link 1](https://towardsdatascience.com/pyspark-in-google-colab-6821c2faf41c)
[Link 2](https://medium.com/@deepa.account/setting-up-spark-ui-with-colab-7bdbc0ac5fa7)
[Link 3](https://naomi-fridman.medium.com/install-pyspark-to-run-on-jupyter-notebook-on-windows-4ec2009de21f)

## Files Descriptions
Capstone_Project_main.ipynb contains analysis and predictions for small dataset.
Capstone_Project_full.ipynb contains analysis and predictions for full dataset.

## Results
In depth analysis to this project can be found [here](https://medium.com/@oluwabori.joba/predicting-churn-with-spark-a-practical-guide-02dedd9e9664)
## Acknowledgements
Datasets was gotten from Udacity for a fictional digital music service called Sparkify

