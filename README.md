# Visualizing the Transformed Data & Pyspark Installation

## I. Visualization on Looker Studio
[Data Source](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) (Yellow Taxi Trips 1-6 2019)\
[Taxi Trips Dashboard](https://lookerstudio.google.com/reporting/6c3a5881-f5c0-4612-9c01-8b0850fb19b8)

<img width="690" alt="Screenshot 2023-03-16 at 14 24 47" src="https://user-images.githubusercontent.com/113230789/225543973-87070e7a-d46b-466a-8c96-fc42fa1d7794.png">

## II. Pyspark Installation on Mac

**Note: make sure python and java are installed**
```
java -version
```
<img width="587" alt="Screenshot 2023-03-16 at 15 12 16" src="https://user-images.githubusercontent.com/113230789/225554778-9d954752-fbe5-43a2-bc19-6a68f60debf2.png">

```
python --version
```
<img width="587" alt="Screenshot 2023-03-16 at 15 12 16" src="https://user-images.githubusercontent.com/113230789/225555164-b671593b-bf5d-4cf3-94a9-dd7ad063835c.png">

If you haven't installed it, you can refer to this video:\
[How to Install Java](https://youtu.be/RfIiBMJqvp8)\
[How to Install Python](https://youtu.be/3-sPfR4JEQ8)

### Steps
1. Download Apache Spark: [here](https://spark.apache.org/downloads.html)
2. Extract the downloaded file
3. Create a 'Spark' folder in your home directory and copy the downloaded files into it
3. create a path into a Spark home in the terminal
``` 
vi . profile 
```
``` 
export SPARK_HOME=/Users/user/Spark/spark-3.3.2-bin-hadoop3
export PATH=$PATH:SPARK_HOME/bin
```
quit from insert screen on terminal `:wq!`\
4. execute .profile `source .profile`\
5. now you can see SPARK_HOME is set up correct there, check with `echo SPARK_HOME`\
6. cd to $SPARK_HOME > bin/pyspark

**Version:**\
<img width="588" alt="Screenshot 2023-03-16 at 15 04 14" src="https://user-images.githubusercontent.com/113230789/225552980-7bc374c0-0549-4ccc-9db1-8d2acc2dd6b3.png">

**Spark context Web UI:**
<img width="1440" alt="Screenshot 2023-03-16 at 15 05 00" src="https://user-images.githubusercontent.com/113230789/225553153-4a91e65c-1782-4cfe-b526-b27a1c9caf15.png">

