# Stanford-CS224n-W2020
This is the homework code for Stanford's [CS224n: Natural Language Processing with Deep Learning course](http://web.stanford.edu/class/cs224n/).
I took this course informally while being a Master's student in the Technion - Israel Institue of Technology, and was interested in NLP as a research field for my thesis.
The code was not checked by official course grading systems. The results are listed below.

## Assignment 1
Introductory assignment - Exploring Word Vectors. Experimented with Glove word embeddings.

## Assignment 2
Implemented Word2vec, 2 approches:
* Cross entropy loss - Naive softmax and loss, as defined in the following equation:

![equation](https://latex.codecogs.com/gif.latex?-%5Cunderset%7Bw%5Cin%20Vocab%7D%7B%5Csum%7Dy_%7Bw%7Dlog%28%7By_%7Bw%7D%29%3D-log%28%5Chat%7By%7D_%7Bo%7D%29%7D)

* Negative sampling loss

![equation](https://latex.codecogs.com/gif.latex?J_%7Bneg-sample%7D%28v_%7Bc%7D%2Co%2CU%29%3D-log%28%5Csigma%28u_%7Bo%7D%5E%7BT%7Dv_%7Bc%7D%29%29-%5Csum_%7Bk%3D1%7D%5E%7BK%7Dlog%28%5Csigma%28-u_%7Bk%7D%5E%7BT%7Dv_%7Bc%7D%29%29)

A 2-d projection of some of the resulting word vectors:

![alt text](https://github.com/orgadhadas/Stanford-CS224n-W2020/blob/master/a2/word_vectors.png)

## Assignment 3

Neural Transition-Based Dependency Parsing, trained for 20 epochs and reached test UAS: 88.97

## Assignment 4

To be completed

## Assignment 5

To be completed
