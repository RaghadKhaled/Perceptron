# Perceptron
Build and train a single and multi Layer Neural Network using Numpy. I implemented it as a programming exercise during a Machine Learning nanodegree at Udacity.

I am very happy to build this neural network, which was a dream of mine three years ago and now it has come true.
## Dataset

Graduate school admissions data. This dataset has three input features: GRE score, GPA, and the rank of the undergraduate school (numbered 1 through 4). 
Institutions with rank 1 have the highest prestige, those with rank 4 have the lowest.
The goal here is to predict if a student will be admitted to a graduate program based on these features.

## Algorithm
Here's the general algorithm for train NN (feedforward and backpropagation) consist of:

- Doing a feedforward operation.
- Comparing the output of the model with the desired output.
- Calculating the error.
- Running the feedforward operation backwards (backpropagation) to spread the error to each of the weights.
- Use this to update the weights, and get a better model.
- Continue this until we have a model that is good.
