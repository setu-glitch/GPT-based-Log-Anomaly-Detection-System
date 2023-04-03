# GPT-based-Log-Anomaly-Detection-System
This repository contains code for a Log Anomaly Detection System that leverages GPT-based language models and machine learning techniques to automatically detect anomalies in log data. The system consists of four main components:

1. Log Parser: A GPT-based language model is used to parse log files and extract relevant information such as log message, severity level, timestamp, etc.

2. Clustering: The log messages are then clustered using KMeans clustering algorithm to group similar messages together and reduce the feature space.

3. Labeling and Embedding: A POS tagger is used to label the log messages with their respective parts of speech. The labeled messages are then combined with their sentence embeddings and word embeddings to create a feature set for anomaly detection.

4. Anomaly Detection: Three different classifiers - Random Forest, CatBoost, and LightGBM - are trained on the feature set to classify log messages as either normal or anomalous.

The repository includes Jupyter notebooks and datasets that walk you through the steps of building and training the Log Anomaly Detection System. The code is well-documented and can be easily customized to fit your specific use case.

---

## Datasets

'Datasets' folder contains four datasets - Apache, BGL, HDFS, and Thunderbird - that are commonly used in log anomaly detection research. These datasets are in the form of log files that contain log messages from various software systems, such as web servers, operating systems, and email clients.

Each dataset is stored in a separate subfolder and includes a README file that provides information about the dataset, such as the system under test, the log format, and the type of anomalies that are present.

Here's a brief overview of each dataset:

1. Apache: This dataset contains log messages from the Apache web server, which is widely used to serve web content.

2. BGL: This dataset contains log messages from the BlueGene/L supercomputer, which is used for scientific research.

3. HDFS: This dataset contains log messages from the Hadoop Distributed File System, which is used for storing and processing large datasets.

4. Thunderbird: This dataset contains log messages from the Thunderbird email client, which is used for sending and receiving email.

These datasets can be used to train and evaluate the performance of the Log Anomaly Detection System implemented in this repository or any other log anomaly detection system.
