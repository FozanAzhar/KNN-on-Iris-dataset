# KNN-on-Iris-dataset
- Exploratory Data Analysis and predictions made on Iris Dataset.<br>
- Model used: KNN (K-Nearest Neighbor)<br>
- A simple dataset to jump on data analysis and visualization and understand the working of KNN<br>
  among the plethora of Machine learning algorithms.
  
  
  ![alt text](https://i.ytimg.com/vi/iOtTpd1R5so/maxresdefault.jpg)
  
  ## KNN Classification Algorithm
1) Load the data<br>
2) Initialize K to your chosen number of neighbors.<br>
3) For getting the predicted class, iterate from 1 to total number of training data points<br>
a) Calculate the distance between test data and each row of training data. Use Euclidean distance as our distance metric
   since it’s the most popular method.The other metrics that can be used are Manhattan, etc.<br>
b) Sort the calculated distances in ascending order based on distance values<br>
c) Get top K rows from the sorted array<br>
d) Get the most frequent class(mode) of these rows<br>
e) Return the predicted class<br>

![alt text](https://media-exp1.licdn.com/dms/image/C5612AQEfdJ6asQfU0g/article-inline_image-shrink_1000_1488/0/1589715473969?e=1659571200&v=beta&t=uz-RgtR42q5D8xvnMnfxc6jE1OP5X5jHBDDmG-dqSO4)

## ACCURACY
Training Accuracy = 98%<br>
Testing Accuracy = 89%
  
  
  



