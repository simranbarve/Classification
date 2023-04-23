# Classifier
#### Introduction 
The aim of Part 1 of this task was to write a supervised learning based classifier to determine whether a given email is spam or not. I did this using a Naive Bayes solution which uses an algorithm to detemine the probability of whether a give message belongs to either the spam or ham class, then the message is then classified based on the Bayesian maximum a posteriori estimate.  
### Naive Bayes Choice
I used the naive bayes algorithm as it was explianed during lectures and I understood it and it produces an accuracy of 0.916 on the test data and therefore, I felt that the effort needed to implement something more complicated such as a neural network would not be worth the time it would ultimately take.
### Naive Bayes explanation 
The naive bayes algorithm uses an equation to work out the probability that a message is either spam or ham based on whether or not specific words are in the message. This is done by looking at training data and finding out the class conditional likelihoods which is the probability of a specific word appearing in a sample of a specific class. After the training is complete a new set of data is inputted (test data) and thr probabilities of whether the message is spam or ham is calculated. 
