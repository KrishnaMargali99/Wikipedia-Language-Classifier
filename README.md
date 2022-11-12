# Wikipedia-Language-Classifier
 Intro to IS Lab: Wikipedia Language Classification
LAB 3 Documentation
Introduction:
The code gives the classification between AdaBoost and Decision tree for the Dutch 
and English languages. Sentences are given as input where some features are included so that 
it can be classified between the English and Dutch languages. 
The model is trained using the AdaBoost and Decision tree using the training data 
where it contains some labels which classifies the languages as en or nl. This data is used to 
classify the languages and train the model based on the training data and also the features that 
were presented to the model for training. 
After the model is trained, The program is again run and then the test file is passed 
without the labels this time so that to see whether the model can predict the languages or not. 
Two learning styles are given : Adaboost and Decision tree 
Steps:
Executing the code :
The code is run on the command line prompt 
While running the code 
Modify run configurations using
For training the model using Decision tree or AdaBoost:
-----------<choose train or predict> <training file name> <hypothesis file> <choose dt or ada>
-------------train train.dat hyp.txt dt
After running the above line again run the program and type the below command to get the 
classification of the test file results.
For predicting the model: 
-----------<choose predict> <hypothesis file> <test file name>
-------------predict hyp.txt test.dat
Features observed in the two languages:
These are the features observed commonly in the dutch and English.
Decision Tree Learning
These supervised learning are a part and used for continuously splitting the data for 
getting the classification based on the classification algorithm.
Here the entropy and the information gain are found to get the best attribute which 
becomes the first root node in the decision tree and then using this root node best true or false 
values are taken and then they become the leaves node for this root node which is the second 
level in the decision tree.
Adaboost Learning:
The root node found here is the stump in the adaboost. Using the stump true and false 
values are taken which becomes the leaf nodes for this stump. Then normal weights are found 
by taking the average of that particular weight by total number of weights and then this 
weight are subtracted from the original weights and they have to be normalized using the 
probability of all the weights and then subtracted to make the sum of all weights equal to 1
