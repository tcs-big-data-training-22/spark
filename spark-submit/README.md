## How to run:
- Open Terminal from Jupyter Notebook
- Set environment
```
cd $USER/spark-submit
set PYSPARK_PYTHON=python
```

- Submit Spark Job
```
/usr/spark/bin/spark-submit hello.py --name "Sample Spark Application" spark-submit hello.py --name "Sample Spark Application"  --conf spark.eventLog.enabled=false --conf spark.sql.shuffle.partitions=2 --master local    --deploy-mode client --master local    --deploy-mode client
```
