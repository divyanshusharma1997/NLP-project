# NLP-project
NLP project on duplicate quora question pair data to distinguish that if 2 given questions are duplicate in meaning or not. This will help the organization to merge the answer in one thread and will be able to provide better response.
Dataset used in this code is here https://www.kaggle.com/datasets/quora/question-pairs-dataset
In this project i have done important preprocessing steps on text string.
The Dataset is very huge it has around 400k rows so it is computationally very expensive even in colab i was able to run programme with
50k rows then i ran out of RAM.
In this project i have used Bag of Word and Word2Vec techniques and results are shown in code. BoW gives better results here.
accuracy with 50k rows is 78-80%. This can be increased if we increase the number of rows fed in our model it will require more computaional power.
further we can do hyper parameter training to further improve the results.
