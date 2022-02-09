# -Diagnosis-of-COVID-19-Machine-learning-
 Diagnosis of COVID-19 and its clinical spectrum

At the beginning of the pandemic, Hospital Israelita Albert Einstein wanted to detect covid cases without using PCR Test, due to an overwhelmed health system.
The goal of this code is to predict the result of a test for a suspected case, with previously collected clinical data.
The performance metrics used are Recall (sensible to false negative), and f1 score. 

There is 4 files, one for the Exploratory Data Analysis, two for the preprocessing step (with and without removing outliers) and one for the modeling part. 


Results : The SGDClassifier model has been used and optimized to predict the result of a test for a suspected case.
The recall and f1 scores are 75%.

# References
https://www.kaggle.com/einsteindata4u/covid19

https://www.youtube.com/channel/UCmpptkXu8iIFe6kfDK5o7VQ
