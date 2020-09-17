# One-day-ahead prediction of hourly global solar radiation.

This project distributes code and files associated to the paper entitled "Binding data mining and expert knowledge for one-day-ahead prediction of hourly global solar radiation"

It includes:
a) description (values) of the 14 centroids used to characterized 14 types of days.
b) demo training dataset and code to conduct the first and second phases of the methodology, and 
c) code to perform the prediction phase, configured with the best models determined in the paper.

Code in R files is prepared to be executed in sequential order (every file offers a specific functionality).

Folders contains:
- *Types of days*: files with two different clustering results. They describe 14 types of days in two (similar) ways.
- *Training system (induce models)*: code to train new models by using new datasets. A demo dataset is available.
- *Prediction system (need models)*: code to predict the hourly global solar ratiation for next day using available models (trained in previous step or those available in this project).
- *Models pretrained (using full dataset)*: models trained by using the full dataset (27K examples). They can be directly used in the prediction step.
