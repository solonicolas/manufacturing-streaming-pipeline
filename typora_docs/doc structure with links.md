# Thesis structure with links

## Introduction 

## Chapter 1 - Streaming Data

### The world of Big Data

- slides Uniud: https://www.oracle.com/it/big-data/what-is-big-data/ + https://searchdatamanagement.techtarget.com/definition/big-data + 

### Batch vs Streaming

- Batch vs Streaming Data: https://www.precisely.com/blog/big-data/big-data-101-batch-stream-processing + https://thenewstack.io/the-big-data-debate-batch-processing-vs-streaming-processing/
- Streaming Analytics : https://databricks.com/glossary/streaming-analytics

### Challenges of Streaming Data

- Data complexity:  https://www.youtube.com/watch?v=_jPKqJ-gaIY + https://www.youtube.com/watch?v=QRRGI4EysSI
- Operations type and System reliability: https://www.youtube.com/watch?app=desktop&v=0C9MHMYyCYY&feature=youtu.be + https://www.youtube.com/watch?v=j1Q7BsOMhG8
- Batch size and windowing: https://softwaremill.com/windowing-in-big-data-streams-spark-flink-kafka-akka/

(https://www.oreilly.com/library/view/streaming-systems/9781491983867/ch04.html)

## Chapter 2 - Different approaches

### Brief recap on DWH and Data Lake

- slides Uniud

### Lambda and Kappa Architectures ("Spaghetti" Architecture) (Cold vs Hot path)

- Spaghetti Architecture: https://data-sleek.com/what-is-spaghetti-architecture-and-how-to-avoid-it/
- Lambda Architecture: https://levelup.gitconnected.com/big-data-lambda-architecture-in-a-nutshell-fd5e04b12acc

- Lambda and Kappa Architectures:  https://towardsdatascience.com/a-brief-introduction-to-two-data-processing-architectures-lambda-and-kappa-for-big-data-4f35c28005bb

### Beyond Lambda: Lake House (Delta Lake)

- Beyond Lambda Architecture: https://databricks.com/glossary/lambda-architecture

### (Data virtualization)

## Chapter 3 - Spark

### What is Spark?

- Spark: https://spark.apache.org/docs/latest/

### RDDs -> Dataframes / Datasets

- Differences: https://www.analyticsvidhya.com/blog/2020/11/what-is-the-difference-between-rdds-dataframes-and-datasets/
- Differences: https://databricks.com/blog/2016/07/14/a-tale-of-three-apache-spark-apis-rdds-dataframes-and-datasets.html

### Spark Streaming -> Spark __Structured__ Streaming

- Continuous Applications: https://databricks.com/blog/2016/07/28/continuous-applications-evolving-streaming-in-apache-spark-2-0.html
- Spark Streaming
  - Docs: https://spark.apache.org/docs/latest/streaming-programming-guide.html
  - Model: https://databricks.com/blog/2015/07/30/diving-into-apache-spark-streamings-execution-model.html
  - Spark Summit 2013 https://www.youtube.com/watch?v=g171ndOHgJ0
  - Spark Summit 2015: https://www.youtube.com/watch?v=d5UJonrruHk
- Spark __Structured__ Streaming (2016)
  - Docs: http://spark.apache.org/docs/latest/structured-streaming-programming-guide.html
  - Model: https://databricks.com/blog/2016/07/28/structured-streaming-in-apache-spark.html
  - Example: https://medium.com/expedia-group-tech/apache-spark-structured-streaming-first-streaming-example-1-of-6-e8f3219748ef
  - Input sources: https://medium.com/expedia-group-tech/apache-spark-structured-streaming-input-sources-2-of-6-6a72f798838c
  - Output sources: https://medium.com/expedia-group-tech/apache-spark-structured-streaming-output-sinks-3-of-6-ed3247545fbc
  - Spark Summit 2016 (streaming to structured): https://www.youtube.com/watch?v=rl8dIzTpxrI
- Spark Streaming vs Spark __Structured__ Streaming: https://dzone.com/articles/spark-streaming-vs-structured-streaming

### Challenges of Streaming Data

 https://www.youtube.com/watch?v=_jPKqJ-gaIY + https://www.youtube.com/watch?v=QRRGI4EysSI

- Checkpoints:  State of Progress (Stateless vs Stateful) and State of Data (only Stateful processing) : https://www.youtube.com/watch?app=desktop&v=0C9MHMYyCYY&feature=youtu.be + https://www.youtube.com/watch?v=j1Q7BsOMhG8

- Windows: slide Dan + https://softwaremill.com/windowing-in-big-data-streams-spark-flink-kafka-akka/ + 

- Azure Windows: https://www.coursera.org/lecture/data-processing-with-azure/selecting-windowing-functions-introduction-IcDV0 + https://docs.microsoft.com/en-us/stream-analytics-query/windowing-azure-stream-analytics

- Watermarks: slide Dan + https://towardsdatascience.com/watermarking-in-spark-structured-streaming-9e164f373e9



## Chapter 4 - Use Case (q3platform)

### Platform overview

### Problem statement

### Proposed solution

- Data source (which dataset , etc...)
- Data ingestion https://kafka-python.readthedocs.io/en/master/
  - Kafka: https://kafka.apache.org/documentation/streams/ + https://www.youtube.com/watch?v=JalUUBKdcA0
  - Kafka examples: https://databricks.com/blog/2017/04/26/processing-data-in-apache-kafka-with-structured-streaming-in-apache-spark-2-2.html, https://databricks.com/blog/2017/04/04/real-time-end-to-end-integration-with-apache-kafka-in-apache-sparks-structured-streaming.html, https://spark.apache.org/docs/latest/structured-streaming-kafka-integration.html
- Data transformation (logics behind the scene)
- Data visualization (Power BI, web applications, etc...)

### Results

## Chapter 5 - On-premise vs Cloud

### Main theoretical differences

- Differences: https://itmanager.space/on-premise-cloud/ + https://www.cleo.com/blog/knowledge-base-on-premise-vs-cloud + https://dynamics.folio3.com/blog/on-premise-vs-cloud-erp-software-difference/

### Performance measures: costs, scalability, fault-tolerance,  privacy, ...

### Experimental evaluation

## Chapter 6 - Machine learning with Streaming Data (optional)

## Conclusion





