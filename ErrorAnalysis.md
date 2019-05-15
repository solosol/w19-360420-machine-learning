# Title
## Course - Section
## Authors

## Distributions of Model Accuracy

## Analysis of different error types



Sam 


K = 5 
Total Average Score after 1000 runs: 94.78%
Standard deviation: 2.337%
Average Precision = 95.67%
Standard Deviation = 7.603%
Average Recall = 92.79%
Standard Deviation = 14.35%


We increased our confidence in our model by repeating the process of choosing the testing and training set (in addition to applying the k nearest neighbor algorithm) 1000 times.

The accuracy changes each time the process is repeated because a new training and testing set is selected each time.  Moreover, each time the classification model is ran the collections.shuffle(fulldataset) shuffles the elements in a list and randomly assigns them new positions.

A false positive is when something is diagnosed as true when, in reality is false. In our case, it is the AI saying that someone has a malignant tumor when they actually have a benign tumor.

A false negative is when a malignant tumor is categorized as benign. This is a big error because it can lead a doctor to not advise the patient the proper steps to remove their cancer cells (thus, the tumor will never be removed or treated). 


Recall refers to the number of true positives (number of positive test results that are correct). In other words, recall is the number of elements that can be considered as relevant. 


A sensible baseline against which we should compare our model's performance is what would the average score would be if we were to guess that every tumor is malignant. 


In the k nearest neighbours algorithm, the accuracy and the level of error depends on the parameter k. Since increasing the value of the k increases the number of points that are considered to be neighbours, the frequency of false positives and negatives increases. 
