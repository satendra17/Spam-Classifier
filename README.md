# SMS-Spam-Classifier

## Description
A simple classifier of SMS to detect whether the SMS is a spam or not. 

## How to run?
1) Open Google Colab and create a new notebook
2) Paste the code given in the files Spam Classifier BOW+Stemming.py in to the notebook
3) Download the dataset from https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection and upload in the files section
4) Run the code by pressing ctrl+enter and check the accuracy score

## Dataset
1) The Dataset used in this is a sample SMS spam classification dataset
2) It is labelled as 'spam' if the message is a spam else labelled as 'ham'
3) It consists of more than 5500 SMS
4) Downloaded from : https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

## Approaches
We take the train-test split as 80/20 respectively.
### 1) Bag of Words 

### 2) TFIDF

## Conclusion
We can see that if we use Bag of words for text preprocessing we get an accuracy score of 98.54% whereas for TFIDF preprocessing we get a less score of 97.13% <br />
Hence Bag of Words is a better approach than TFIDF for SMS Spam classification on this dataset
