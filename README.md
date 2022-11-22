 In order to run my experiments, you first have to run the reformat data code, which basically removes the header and classification column from the data.

The three data sets I used are linked below:

https://archive.ics.uci.edu/ml/datasets/Iris

https://archive.ics.uci.edu/ml/datasets/Raisin+Dataset

https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset

Following Cleaning the data you must change line 118 in k_means_plus_ ls to represent the path of the new data file that was created. Then change line 119 to the desired number of centroids. 

I included the cleaned iris.csv file because it is extremely small. If you want to run it with this file you do not need to clean the data as I already have.

I did not copy any code from other repos as there was no official code for this paper. However, I based my implementation of the K-means++ function (kpp) on code from this link https://www.geeksforgeeks.org/ml-k-means-algorithm/
