# Imbalanced_Data-GFRNN_Classifier

This is my Matlab implementation of the GFRNN classifier for handling Imbalanced datasets. This algorithm was proposed in 2015 by Yujin Zhu, Zhe Wang and Daqi Gao.

Click <a href="http://www.sciencedirect.com/science/article/pii/S0950705115003548">Here</a> to see the GFRNN paper.

Short description of contained codes:

- <b>main_GFRNN.m</b>: contains the implementation of GFRNN.

- <b>GMCalc.m</b>: is a function that calculates the Geometric Mean of classification by taking into input the predicted labels and the actual labels. The geometric mean is a common way to evaluate the effectiveness of a classification algorithm on imbalanced datasets.

- <b>Example_Imbalanced_Dataset_Test.mat</b>: and "Example_Imbalanced_Dataset_Train.mat" are two matrixes created for educational purposes to demonstrate how to implement GFRNN on a given dataset.
