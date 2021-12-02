# The K-Nearest Neighbors Algorithm
![](https://www.coryjmaklin.com/media/machine-learning-algorithms-part-6-k-nearest-neighbors-in-python-1.png)

## What is k-NN?

K nearest neighbors is a simple algorithm that stores all available cases and classifies new cases based on a similarity measure (e.g., distance functions)One of the simplest decision procedures that can be used for classification is the nearest neighbour (NN) rule. It classifies a sample based on the category of its nearest neighbour. The nearest neighbour based classifiers use some or all the patterns available in the training set to classify a test pattern

When to use KNN:

you can use the KNN algorithm for applications that require high accuracy but that do not require a human-readable model. The quality of the predictions depends on the distance measure.

Advantages:
+ Quick calculation time.
+ Simple algorithm – to interpret.
+  Versatile – useful for regression and classification.
+  High accuracy – you do not need to compare with better-supervised learning models.

    
Disadvatages:
+ Does not work well with a large dataset: ...
+ Does not work well with a high number of dimensions


## How does k-NN work?

KNN works by finding the distances between a query and all the examples in the data

+ 1. The optimal K value usually found is the square root of N, where N is the total number of samples
+ 2. calculating the distance between any two points.
+ 3. Majority vote on a class labels based on the nearest neighbor list

## The Distance
The most popular distance measure used for this algorithm is the Euclidean Distance. It is calculated as the square root of the sum of the squared differences between a new point and an existing point across all input attributes.
![](https://i.stack.imgur.com/RtnTY.jpg)
![image](https://user-images.githubusercontent.com/95150718/144479220-d35d58a4-2fc7-4ce3-b5b3-26459cf7214a.png)

