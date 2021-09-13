# Thesis structure

## Introduction 

## Chapter 1 - Streaming Data

- The world of Big Data
  - The "Vs" of big data
- Batch vs Streaming
- Streaming analytics challenges

  - Data and operations complexity
  - System reliability
  - Batch size and windowing

@unpublished{intro_to_big_data,
    url = {https://github.com/dslab-uniud/teaching},
}

@online{what_is_big_data_oracle,
    url = {https://www.oracle.com/big-data/what-is-big-data/}
}

@online{what_is_big_data_cloud,
    url = {https://cloudit-eg.com/what-is-big-data-and-how-does-it-work/}
}

@techreport{3v_concept,
  url = {http://blogs.gartner.com/doug-laney/files/2012/01/ad949-3D-Data-Management-Controlling-Data-Volume-Velocity-and-Variety.pdf}
}

@online{bucket_vs_faucet,
    url = {https://www.g2.com/articles/what-is-a-data-lake}
}

@online{batch_vs_stream_data_precisely,
    url = {https://www.precisely.com/blog/big-data/big-data-101-batch-stream-processing}
}

@online{batch_vs_stream_data_newstack,
    url = {https://thenewstack.io/the-big-data-debate-batch-processing-vs-streaming-processing/}
}

@online{streaming_analytics,
    url = {https://databricks.com/glossary/streaming-analytics}
}

@online{stream_gartner,
    url = {https://www.gartner.com/en/information-technology/glossary/real-time-analytics}
}

@online{stateless_vs_stateful,
    url = {https://www.youtube.com/watch?app=desktop&v=0C9MHMYyCYY&feature=youtu.be}
}

@online{streaming_challenges,
    url = {https://databricks.com/session/easy-scalable-fault-tolerant-stream-processing-with-structured-streaming-in-apache-spark-continues}
}

@online{windows,
    url = {https://softwaremill.com/windowing-in-big-data-streams-spark-flink-kafka-akka/}
}

## Chapter 2 - Different approaches

- Brief recap on DWH and Data Lake
- Lambda and Kappa Architectures ("Spaghetti" Architecture) (Cold vs Hot path)
- Beyond Lambda: Lake House (Delta Lake)
- (Data virtualization)

## Chapter 3 - Spark

- What is Spark?
- RDDs -> Dataframes / Datasets
- Spark Streaming -> Spark __Structured__ Streaming
- Challenges of Streaming Data

  - Checkpoints:  State of Progress (Stateless vs Stateful) and State of Data (only Stateful processing) 

  - Windows
  - Watermarks

## Chapter 4 - Use Case (Q3-platform)

- Platform overview
- Problem statement
- Proposed solution
  - Data source (which dataset , etc...)
  - Data ingestion
  - Data transformation (logics behind the scene)
  - Data visualization (Power BI, web applications, etc...)
- Results

## Chapter 5 - On-premise vs Cloud

- Main theoretical differences
- Performance measures: costs, scalability, fault-tolerance,  privacy, ...
- Experimental evaluation

## Chapter 6 - Machine learning with Streaming Data (optional)

- ....
- .....

## Conclusion





