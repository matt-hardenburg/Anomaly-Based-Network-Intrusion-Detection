# Anomaly-Based-Network-Intrusion-Detection
This is a semester long research project done for my Data Driven Security Analytics course.

The goal of this project is to determine network attacks through anomaly detection with machine learning. The project intakes an array of data gathered from network traffic, denoises via an autoencoder before passing the data to the models for analysis. There are four models employed: reconstruction error from the autoencoder, a KMeans model, a Gaussian Mixture model, and an isolation forest. The four separate scores are then taken and passed to a linear regression model, which determines the optimal weights and produces a binary anomaly detection.

The model had acceptable metrics regarding performance, but suffered a high amount of false positives. I have plans for a future iteration of this project employing a General Adversarial Network to aid in identifying anomalous signals.
