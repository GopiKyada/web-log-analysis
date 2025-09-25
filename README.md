# Web Server Log Analysis (PySpark + Hadoop)

## Dataset
- NASA HTTP Web Server Logs (July + August 1995)  
- Download: ftp://ita.ee.lbl.gov/traces/NASA_access_log_Jul95.gz

## Steps
1. Upload logs to HDFS:
   ```bash
   hdfs dfs -mkdir /logs
   hdfs dfs -put nasa_log.txt /logs/
