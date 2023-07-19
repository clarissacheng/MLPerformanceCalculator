# ML Performance Calculator App

This app calculates model performance metrics like accuracy, balanced accuracy, precision, recall, MCC, F1, and Cohen Kappa from inputted actual and predicted values. Available at: https://ml-performance-calculator.streamlit.app/ 

## Inspiration

To assist each other in the technical analysis of whether certain stocks would rise or fall each day, my brother and I would input into spreadsheets our predictions and record the actual outcome the next day. With our data, I decided to build this project which indicates if we're making progress in our predictions and provides statistics for our progress. By recording how well we are at predicting the trends of certain stocks, we'd be able to work on the accuracy of our indicators to increase our chances of accurately predicting the trends of stocks in the stock market. 

## Implementation

Users are provided example data to test the metrics if they don't have actual and predicted data to test. After entering their own data or using example data, a classification performance metrics are calculated with machine learning. 

## Classification Metrics

Confusion matrix - Confusion Matrix is a tabular visualization of the ground-truth labels versus model predictions. Each row of the confusion matrix represents the instances in a predicted class and each column represents the instances in an actual class. Confusion Matrix is not exactly a performance metric but sort of a basis on which other metrics evaluate the results.

Accuracy - Accuracy is perhaps the simplest metric to use and implement and is defined as the number of correct predictions divided by the total number of predictions, multiplied by 100. 

Precision - Precision is the ratio of true positives and total positives predicted.

Recall - Recall is essentially the ratio of true positives to all the positives in ground truth.

F1 - The F1-score uses a combination of precision and recall and is basically the harmonic mean of the two.

Further information about metrics can be found here: https://neptune.ai/blog/performance-metrics-in-machine-learning-complete-guide
