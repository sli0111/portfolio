# Data Science Portfolio 
https://sli0111.github.io/portfolio/

This portfolio is a compilation of notebooks in which I explore and solve data science science problems.  The projects below are divided into several main categories: capstone, image processing, natural language processing, parallel computation, data exploration, and tutorials.

## Capstone

### Cancer Drug Response Prediction

[Website](https://www.ischool.berkeley.edu/projects/2021/screen-ahead-rx)

For 7 out of 10 cancer patients, the first cancer drug fails to work for them.  In this project,  I worked with a team to develop novel drug embeddings that capture drug structure using NLP models: bi-directional RNN autoencoder and BERT.  When the drug embeddings are combined with cancer genetics, we saw improve cancer response prediction.


## Image Processing

### Prediction of COVID-19 from CT Scans

[Github](https://github.com/sli0111/MIDS-251-2021-Final-Project) [nbviewer](https://nbviewer.jupyter.org/github/sli0111/MIDS-251-2021-Final-Project/blob/main/ResNet18/ResNet18.ipynb)

COVID-19 pandemic shook the world as it spread nearly out of control and many argue that early detection would have been key to mitigating it.  In this project, transfer learning of deep convolutional neural networks (CNN) are applied to CT Scan slices of lungs to detect COVID-19, in comparison to a normal lung or a lung with pneumonia.  The project demonstrates an end-to-end pipeline from data ingestion, training, deployment, and inference on a edge device.  We found that transfer learning CNN could be highly effective on medical images.

## Natural Language Processing

### Entity Relation Extraction in Clinical Text

[Github](https://github.com/sli0111/w266-2021-Medical-Relationship-Extraction-with-Bio-Clinical-BERT-and-Longformer)  [nbviewr](https://nbviewer.jupyter.org/github/sli0111/w266-2021-Medical-Relationship-Extraction-with-Bio-Clinical-BERT-and-Longformer/blob/main/train_longformer_cls.ipynb)

As more hospitals begin to capture notes in Electronic Health Records (EHR), this provides an opportunity to use machine learning to extract medical history out of unstructured clinical text and provide physicians with data to make better decisions.  This project applies pretrained BERT models: BioClinical BERT and Longformer to a custom model architecture to classify relations between entities in clinical text.  

### Random Acts of Pizza (ROAP)

[Github](https://github.com/sli0111/raop) [nbviewr](https://nbviewer.jupyter.org/github/sli0111/raop/blob/main/Baseline_and_Logistic_Regression_Model_v4.ipynb)

A popular subreddit is random acts of pizza, where strangers can request for free pizza from other strangers.  People's request are in the form of text data thus natural language processing was applied using the nltk package and unsupervised text clustering with KMeans algorithm to extract features.  Extracted features were used with a logistic regression model algorithm to predict which post would receive pizza.

### Tweet Sentiment Extraction

[Github](https://github.com/sli0111/tweet_sentiment_extraction) [nbviewer](https://nbviewer.jupyter.org/github/sli0111/tweet_sentiment_extraction/blob/main/Tweet_Sentiment_Extraction_v1.ipynb)

Given the wide spread use of social media, influential tweets or messages could initiate huge positive or negative public reactions.  However which words lead to those sentiment descriptions?  This project utilizes text preprocessing with nltk and a Naive Bayes classifier to predict which words or phrases most reflect that sentiment.


## Parallel Computational Machine Learning

[Github](https://github.com/sli0111/flight_delay) [nbviewer](https://nbviewer.jupyter.org/github/sli0111/flight_delay/blob/main/Team%2020%20-%20Algorithm%20Exploration-6m-UnderSample.ipynb)

### Prediction of Flight Delay

Flight delays cost the US economy as much as $32 billion dollars each year.  This project applies parallel computing with PySpark to develop a machine learning pipeline that uses gradient boosted decision trees to predict flight delays.  Ultimately, this would improve chances of airports making the appropriate manuevers when a flight delay would occur.


## Data Exploration

### Lyft Bikeshare

[Github](https://github.com/sli0111/lyft_bikeshare) [nbviewer](https://nbviewer.jupyter.org/github/sli0111/lyft_bikeshare/blob/gh-pages/Lyft%20Bikeshare.ipynb#)

The bikeshare industry is still growing especially in modern cities.  This project utilizes the Lyft Bikeshare dataset on the Google Gloud Platform and applies BigQuery, Jupyter Notebooks, Pandas, and Seaborn to explore opportunities to increase membership.

## Tutorials

### An Introduction to Digit Classification with KNN

[Github](https://sli0111.github.io/MNIST_KNN/)

Handwritten digits are used on bank checks, medical applications, and mail but vary in depending on the individual.  In this project, a the MNIST dataset of handwritten digits images are classified a number between 0 to 9 using the K-nearest neighbors algorithm.

