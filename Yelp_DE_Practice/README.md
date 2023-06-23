# YELP data set Data Engineering and Machine Learning Practice (GCP)

#### keyworks: Hadoop, HIVE, Spark, GCP, BigQuery, CloudStorage, DataProc, Python, SQL, Pandas, Parquet

### Project Description:
Practiced ELT and ML in GCP. Obtained expertise with GCP **Data Warehouse** service: **Big Query**; GCP managed **hadoop** cluster service: **DataProc**; GCP storage service: **Cloud Storage**, GCP ML/AI services: **Vertex AI**. 
1. experienced with DataProc, to load the Yelp review data into **hadoop** file system, transformed data with **Spark** and load the data into **BigQuery**. Performed some **EDA** in **DataProc**.
2. Used **Vertex AI** workbench and **BigQuery** to explore difference ML model's performance and explored the text reviews.

### Key Practices In This project:
1. Data Extraction: Using **Kaggle API** to download the Yelp Dataset to DataProc Master node. (>8GB after unzip)
2. Data Transformation: Upload the unzipped data to **Hadoop File System**; Used **pyspark** to clean the transform the dataset, then load into **HIVE** tables in Hadoop. 
3. Performed Exploratory Data Analysis with Pyspark and Pandas, found the best 10 popular restaurants in Philadelphia.
4. Created DataLayer, by de-normalizing the 5 tables ( processed >320 million records); saved the data as **Parquet** format in **CloudStorage** and loaded into **BigQuery**. (Connected Dataproc cluster to CloudStorage directly, used CloudStorage as DataLake)
5. Use Vertex AI Workbenck build ML / NLP models with the data in BigQuery;
   1. Tokenized the text reviews, experimented with different kinds of ML models : Naive-Bayes Classifier, logistic regression Classifier, RandomForest Classifier.
   2. Explored the text reviews in the dataset and found some important information. 


