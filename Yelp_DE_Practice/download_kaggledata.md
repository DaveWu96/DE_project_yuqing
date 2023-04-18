`kaggle datasets download -d yelp-dataset/yelp-dataset`

![2023-04-17_21-45-55.png](images%2F2023-04-17_21-45-55.png)

++++++++++++++++++++++++++++ how to install kaggle API+++++++++++++++++++++++++++++++++++

https://github.com/Kaggle/kaggle-api

++++++++++++++++++++++++++++unzip file+++++++++++++++++++++++++++++++++++

`unzip yelp-dataset.zip `



++++++++++++++++++++++++++++upload to hdfs+++++++++++++++++++++++++++++++++++

`hadoop fs -mkdir user/pytrick/`

`hdfs dfs -mkdir user/pytrick/yelp_data/`

`hdfs dfs -put yelp_academic_dataset* user/pytrick/yelp_data/`






### clean and load data into HIVE. 
Useful links https://www.guru99.com/data-extraction-hive.html#:~:text=Using%20Hive%20as%20data%20store,Hive%20tables%20by%20creating%20schemas.&text=In%20this%2C%20we%20are%20going%20to%20load%20JSON%20data%20into,values%20stored%20in%20JSON%20schema.


---------------below are for my own recors---------------

cat  ~/.bashrc

nano ~/.bashrc
export PATH="/home/pytrick/.local/bin:$PATH"

source ~/.bashrc
