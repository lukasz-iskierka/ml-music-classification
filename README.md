# Music Genre Classification

### Task:
Develop machine learning algorithms that can predict a music genre for each sample, using the data music.csv

### Business goal:
To make the prediction for the music genre dataset; minimising error and maximising accurate classification. 

### Data used:
This dataset is an adapted version of a publicly available resource, which can be accessed at: [GTZAN Dataset on Kaggle.](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/dat)

It contains:

CSV files (2) - Each file contains features of audio files. The first file, **features_30_sec.csv**, contains a mean and variance for multiple attributes extracted from 30-seconds-long samples of audio files. The second file, **features_3_sec.csv**, contains 10 times more data, due to each each song being split into 3 seconds samples. 

For the purpose of this project, I will refer to the features_30_sec.csv as **30s data** and, conversely, **3s data** to the features_3_s.csv dataset.  

Mel Spectrograms - A visual representation for each audio file that could be used in NNs.

An original GTZAN dataset collection of 100 audio files for each genre (10).