# Signal-to-Word-for-HAR
Using SAX for Dimensionality reduction of multichannel signal data before activity classification

Dataset: UCI HAR DATASET : https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

 Human Activity Recognition (HAR) using wearable sensor data is a pivotal area in ubiquitous computing. Raw time-series signals, however, are high-dimensional and contain noise, posing challenges for classification models. This paper proposes a framework that transforms sensor signals into a symbolic representation, or “words,” using Symbolic Aggregate Approximation (SAX). This method effectively reduces dimensionality and abstracts signal features. We utilize the public UCI HAR dataset to demonstrate our approach. The generated symbolic sequences are then fed into a deep learning model to classify human activities. Our experiments show that this signal-to-word conversion not only simplifies the classification task but also achieves competitive accuracy, highlighting its potential for creating robust and efficient HAR systems
