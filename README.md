This is an ongoing notebook, from  a kaggle competition (https://www.kaggle.com/c/expedia-hotel-recommendations/data). The goal is to predict the prefered hotel cluster of the users. I keep updating this notebook. 

The **training data** is a dataset of size **3.8 GB of more than 37 million** samples (users log data) which includes information such as the user country, hotel country, search date of checkin, search date of check out, etc. 

The test set includes more that 250k users log data. 

Due to the size of the training data, python libraries such as pandas and sklearn will fail, so here I use the python wrapper of **Apache Spark (pyspark)**. Also, I will use the distributed computing service of Amazon, **Elastic Map Reduce (EMR)**, for faster analysis and building of machine learning models. 
