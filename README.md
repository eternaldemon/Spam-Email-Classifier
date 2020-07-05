# Spam-Email-Classifier
This repository contains the 2 different methods that I used to classify spam mail on the basis of the given text in them.

<b>
Dataset Used : emails.csv
  
Note: This dataset contains 2 columns named text and spam. It has around 5500 entries with huge sentences in each entry.


    Spam Classifier using the following 2 methods:

    1. Basic Version - Using Support Vector Classifier under SVM and GridSearchCV
    2. Advanced Version - Using LSTM and Embeddings


    Note: Advanced version will take a lot of time to train even on Google Colab but will be able to get more higher accuracy than that of Basic model, even though basic model's accuracy reaches as high as 98.77%

    Validation Accuracy:
    1. Basic Version - 98.77% after 240 iterations
    2. Advanced Version - 99.21% after 12 epochs(2 shown and 10 were saved and loaded weights from a previous training session)
      
  </b>
