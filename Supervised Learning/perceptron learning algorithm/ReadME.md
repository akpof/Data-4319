# Perceptron Learning ALgorithm (PLA)

![image](https://user-images.githubusercontent.com/95150718/144483171-0a5414ee-9eeb-4b93-b499-e5796149a6a8.png)


## What is the Perceptron?

The Perceptron algorithm is a two-class (binary) classification machine learning algorithm. It is a type of neural network model, perhaps the simplest type of neural network model. it was invented in 1958 by psychologist Frank Rosenblatt and the perceptron is an algorithm for supervised learning of binary classifiers. It is a type of linear classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.


## How does the Perceptron work

A Perceptron is simply composed of a single layer of TLUs,6 with each TLU connected to all the inputs. When all the neurons in a layer are connected to every neuron in the previous layer (i.e., its input neurons), it is called a fully connected layer or a dense layer. To represent the fact that each input is sent to every TLU, it is common to draw special passthrough neurons called input neurons: they just output whatever input they are fed. All the input neurons form the input layer. Moreover, an extra bias feature is generally added (x0 = 1): it is typically represented using a special type of neu‐ron called a bias neuron, which just outputs 1 all the time. A Perceptron with two inputs and three outputs is represented below. This Perceptron can classify instances simultaneously into three different binary classes, which makes it a multi‐output classifier.

![image](https://user-images.githubusercontent.com/95150718/144484160-e734fbfe-71db-4530-b1f0-8de5e055015f.png)

