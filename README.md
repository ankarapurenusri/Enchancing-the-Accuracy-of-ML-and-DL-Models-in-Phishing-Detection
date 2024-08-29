# Enchancing-the-Accuracy-of-ML-and-DL-Models-in-Phishing-Detection
Classfication of URL using Machine learning and Deep learning

Objective :
A typical social engineering technique that imitates reliable unified resource locators (URLs) and online pages is the creation of phishing websites. This research aims to train deep neural networks and machine learning models using a dataset that has previously had features extracted to predict phishing websites. A dataset is created by collecting website URLs, both benign and phishing. Every model's performance level is quantified and contrasted. A typical social engineering technique that imitates reliable unified resource locators (URLs) and online pages is the creation of phishing websites. A phishing website is a standard social engineering method that mimics trustful uniform resource locators (URLs) and web pages. This project aims to train machine learning models and deep neural nets on the dataset created to predict phishing websites. Both phishing and benign URLs of websites are gathered to form a dataset. The performance level of each model is measured and compared. A phishing website is a standard social engineering method that mimics trustful uniform resource locators (URLs) and web pages. 

Data Collection : 
The dataset was obtained from https://www.unb.ca/cic/datasets/url-2016.html, containing many datasets, including spam, malware, phishing, and defacement. After filtering all datasets, we have used phishing and Bening solely for this study. We have over 7,000 rows of benign data and over 7000 rows of phishing. All of the datasets, together with the phishing and being dataset that has been filtered, have been submitted to the data files. Features from the URLs have already been extracted into this data.
Model & training : 
The data is divided into 80% for training and 20% for testing before models are applied. As the target column only contains 2 features. Phishing is ranked as a categorization problem of one, while benign is ranked as zero. The models used for this project are listed below. 
Decision Tree
Random forest
XGBoost Classifier
Support vector machine
Ensemble model
LSTM

End results :
It is evident from the results that the XGBoost classifier fared better than the other models, with a test accuracy of 98.7% and a train accuracy of 100%

Future work :
For additional research on initiatives of this kind. It is possible to employ more feature-rich, complex data. Deep analysis of the data can also be achieved by using more advanced deep learning techniques. Another model that works well with this type of data is transfer learning.


