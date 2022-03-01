# Part I. K-means clustering
## Introduction
K-means is one of the widely used unsupervised learning algorithms that solve the
well-known clustering problem. The procedure follows a simple and easy way to classify a
given data set through a certain number of clusters (assume k clusters). The main idea is to
define k centers, one for each cluster. These centers should be placed in a cunning way
because of different location causes different result.

# Part II. Principal Component Analysis (PCA)
## Introduction
Principal Components Analysis (PCA) is a dimensionality reduction algorithm that can be used
to significantly speed up your unsupervised feature learning algorithm. For example, when you
train your model on a dataset such as images, some of our data points may be meaningless in
explaining our desired target variable. Therefore, we refer to drop them from our training.

#### Task1: Users to Movies
- In this task, you will work with a Users-to-Movies example (as shown below) from
http://web.stanford.edu/class/cs246/slides/06-dim_red.pdf. Each row contains the scores
provided by a user while each column has the scores given by different users on the same
movie. The first 4 users prefer Science Fiction and the others prefer Romance. You will need
to implement the classic PCA algorithm and calculate the features after PCA.

#### Task2: Human Faces
- In this assignment, you will need The Labeled Faces in the Wild dataset which is designed
for the face recognition task. The dataset containing images of faces. Each image is a 62x47
pixel array. The images are read into a matrix. The rows of the matrix are the images
(examples). The features (columns) are the pixels. Each example is represented by a vector
of real numbers of length 2914, listing the pixels from left to right, row by row, from top to
bottom.
https://scikit-learn.org/stable/datasets/index.html#labeled-faces-in-the-wild-dataset
