# Network Anomaly Detection
This code implements various clustering algorithms for network anomaly detection using the KDD Cup 1999 dataset, including K-Means, Normalized Cut, DBSCAN, and Agglomerative clustering.
This project focuses on network anomaly detection using the KDD Cup 1999 dataset. The goal is to implement various clustering algorithms, including K-Means, Normalized Cut, DBSCAN, and Agglomerative clustering, to identify anomalies in network traffic data. The code implements data preprocessing, clustering algorithms, and evaluation metrics to assess the accuracy of anomaly detection. A detailed report is provided, illustrating the implementation steps and analysis of the results.

## Project Structure 
(College Group Project)

The project consists of the following components:

1. Dataset Download and Format Understanding:

- The dataset contains network traffic data with multiple features.
2. Data Preprocessing and Clustering using K-Means and Normalized Cut:

- Categorical features in the dataset are converted to numerical representation.
- K-Means clustering is applied with different K values to detect anomalies in the network traffic data.
- The Normalized Cut algorithm is used for clustering the preprocessed data.
3. Evaluation Metrics:

- Precision, recall, F1 score, pairwise measures, and conditional entropy are used to evaluate the quality of the clustering models.
4. New Clustering Algorithm:

- DBSCAN and Agglomerative clustering algorithms are chosen as additional techniques for anomaly detection.
- The new clustering algorithms are implemented and evaluated.
## Usage
1. Download the KDD Cup 1999 dataset and place it in the designated directory.

2. Run the code implementation, which includes the following steps:

- Preprocess the dataset by converting categorical features to numerical representation.
- Apply K-Means clustering with different K values to detect anomalies.
- Use the Normalized Cut algorithm for clustering the preprocessed data.
- Evaluate the clustering models using precision, recall, F1 score, pairwise measures, and conditional entropy.
3. Refer to the project report for detailed information, analysis, and results.
