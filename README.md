#  NLP for Text Classification ( tweet is about a real disaster)
This repository focuses on using Natural Language Processing (NLP) to classify whether tweets are related to real-life disasters or not using Python.
<p align="center"><img width="600" src = "https://github.com/user-attachments/assets/f23d45ee-f3aa-4cab-a26f-30c652011745"></p>

## Overview
Text classification เป็นหนึ่งในงานที่สำคัญใน Supervised machine learning (ML) เป็นกระบวนการในการกำหนดแท็ก/หมวดหมู่ให้กับเอกสาร ซึ่งช่วยให้เราสามารถจัดโครงสร้างและวิเคราะห์ข้อความโดยอัตโนมัติ ในบทความนี้จะใช้ dataset “Natural Language Processing with Disaster
 Tweets” ซึ่งเราจะคาดการณ์ว่าทวิตนั้นเกี่ยวกับภัยพิบัติหรือไม่โดยใชโมเดล Logistic Regression และ Naive Bayes โดยเปรียบเทียบ Bag-of-Words รวมกับ Tf-Idf และ Word Embedding รวมกับ Word2Vec

## Getting Started
To run this app on jupyter notebook or Google Colab, follow these steps:

1. **Importing Libraries** 
- The first step is to import libraries, such as pandas, numpy, seaborn, matplotlib, nltk ,etc
2. **Loading the data set** 
- The data set that we will be using for this article is the famous “Natural Language Processing with Disaster Tweets” data set where we’ll be predicting whether a given tweet is about a real disaster (target=1) or not (target=0)
3. **Exploratory Data Analysis(EDA)**
- EDA : provides an overview of the data, key words, total word count, word distribution, and distinctive features that should be presented or are beneficial to the model.
4. **Text pre-processing**
- Before we move to model building, we need to preprocess our dataset by cleaning texts, removing stop words, removing punctuations & special characters, and applying lemmatization
5. **Extracting vectors from text (Vectorization)**
- Vectorization is the process of convert text data into numerical data or vectors because working with text data is challenging when building machine learning models, as these models require well-defined numerical data. Bag-of-Words(with Tf-Idf) and Word Embedding (with Word2Vec) are methods for converting text data to numerical data.
6. **Running ML algorithms**
- Train a machine learning model on the vectorized dataset and test it.


##
This project serves as an introductory example of using NLP for disaster tweet classification. Further improvements might be required to achieve higher accuracy and robustness.
