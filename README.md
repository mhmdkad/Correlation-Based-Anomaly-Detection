# Correlation-Based-Anomaly-Detection
Correlation Based Anomaly Detection in Industrial Control Systems (ICSs)

The work will focus on the collective anomalies found in a given dataset by extracting windows from time-series data and analyzing the correlation between the variables, allowing the detection of anomalous patterns within the window frame utilizing Multivariate Gaussian Distribution. An automatic window size detection was suggested using LTSM-AE and was put under test. At first, the dataset is segmented into different window frames. Correlation is extracted from each until getting the desired format to model the multivariate Gaussian distribution and allow the detection of later anomalies. The study employs a specific dataset, The Secure Water Treatment (SWaT) dataset, which is used in industrial control systems to evaluate the effectiveness of the study. After experimenting, the results came as follows, the LSTM-AE model recommends a window size of 8 based on reconstruction accuracy. However, further investigation reveals that a window size of 128 yields superior results in terms of detecting latent correlations and identifying anomalies. The proposed model achieved comparable precision and F1 scores to the linear SVM. (supervised) approach while outperforming INNE (unsupervised) in terms of precision and F1 score. This research addresses the challenge of collective anomaly detection by extracting windows and leveraging correlation analysis. Window size detection and correlation computation were part of the challenges. The correlation-based model showed to be competing with other machine learning models commonly in use nowadays.
