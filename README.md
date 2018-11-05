# K-Means_Influx
 Using K-Means for anomaly detection for time series data with InfluxDB and Chronograf
 
### Data: 
 EKG Data from: 
 https://www.kaggle.com/ecerulm/apneaecg

### Please view the following blogs for more info on this repo: 
https://www.influxdata.com/blog/why-use-k-means-for-time-series-data-part-one/
https://www.influxdata.com/blog/why-use-k-means-for-time-series-data-part-two/

### Files: 
 #### EKG Data with anomaly in line protocol (data ingest format for InfluxDB):
 anomaly.txt
 #### EKG Data without anomaly in line protocol (data ingest format for InfluxDB):
 norm.text
 #### Use Kmeans to reconstruct the data, set threshold, detect anomalies, write error to InfluxDB with python CL:
 Anomaly_Detection.ipynb
