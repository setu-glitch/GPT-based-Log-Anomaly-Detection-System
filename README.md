# GPT-based-Log-Anomaly-Detection-System
This repository contains code for a Log Anomaly Detection System that leverages GPT-based language models and machine learning techniques to automatically detect anomalies in log data. The system consists of four main components:

1. Log Parser: A GPT-based language model is used to parse log files and extract relevant information such as log message, severity level, timestamp, etc.

2. Clustering: The log messages are then clustered using KMeans clustering algorithm to group similar messages together and reduce the feature space.

3. Labeling and Embedding: A POS tagger is used to label the log messages with their respective parts of speech. The labeled messages are then combined with their sentence embeddings and word embeddings to create a feature set for anomaly detection.

4. Anomaly Detection: Three different classifiers - Random Forest, CatBoost, and LightGBM - are trained on the feature set to classify log messages as either normal or anomalous.

The repository includes Jupyter notebooks and datasets that walk you through the steps of building and training the Log Anomaly Detection System. The code is well-documented and can be easily customized to fit your specific use case.
