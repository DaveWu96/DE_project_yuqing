# YELP data set Data Engineering and Machine Learning Practice (GCP)

#### Keywords: Hadoop, HIVE, Spark, GCP, BigQuery, CloudStorage, DataProc, Python, SQL, Pandas, Parquet

### Project Summary:
- Implemented Extract, Load, Transform (ELT) and Machine Learning practices using Google Cloud Platform (GCP). Enhanced expertise in GCP Data Warehouse service (Big Query), GCP managed Hadoop cluster service (DataProc), GCP storage service (Cloud Storage), and GCP ML/AI services (Vertex AI).

### Key Achievements:
1. Leveraged DataProc to load Yelp review data into Hadoop file system, transformed data using Spark, and uploaded it to BigQuery. Conducted exploratory data analysis (EDA) within DataProc.
2. Utilized Vertex AI workbench and BigQuery to compare different ML model performances and scrutinized text reviews.

### Project Tasks:
1. **Data Extraction**: Utilized Kaggle API to download the Yelp Dataset (>8GB post-unzipping) to the DataProc Master node.
2. **Data Transformation**: Uploaded unzipped data to Hadoop File System; employed pyspark for data cleaning and transformation, then loaded it into HIVE tables in Hadoop.
3. **Exploratory Data Analysis**: Executed Exploratory Data Analysis using Pyspark and Pandas, identifying the top 10 popular restaurants in Philadelphia.
4. **Data Layer Creation**: Created a Data Layer by de-normalizing five tables (processed >320 million records); saved data as Parquet format in Cloud Storage and loaded it into BigQuery. DataProc cluster was connected directly to CloudStorage, using it as a Data Lake.
5. **Machine Learning/NLP Modeling**: Used Vertex AI Workbench to build ML/NLP models with data in BigQuery;
   1. Executed text review tokenization, experimented with various ML models including Naive-Bayes Classifier, Logistic Regression Classifier, and RandomForest Classifier.
   2. Conducted detailed text review exploration in the dataset to gather significant insights.
