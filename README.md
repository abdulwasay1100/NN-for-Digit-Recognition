# Neural-Networks-for-Handwritten-Digit-Recognition-Binary

#Neural Networks
I've implemented logistic regression. This was extended to handle non-linear boundaries using polynomial regression. For even more complex scenarios such as image recognition, neural networks are preferred.

**Problem Statement:**
In this assignment, I've used neural network to recognize two handwritten digits, zero and one. This is a binary classification task. Automated handwritten digit recognition is widely used today - from recognizing zip codes (postal codes) on mail envelopes to recognizing amounts written on bank checks. You will extend this network to recognize all 10 digits (0-9) in a future assignment.

**Dataset:**
The load_data() function shown below loads the data into variables X and y

The data set contains 1000 training examples of handwritten digits, here limited to zero and one.
Each training example is a 20-pixel x 20-pixel grayscale image of the digit.
Each pixel is represented by a floating-point number indicating the grayscale intensity at that location.
The 20 by 20 grid of pixels is “unrolled” into a 400-dimensional vector.
Each training example becomes a single row in our data matrix X.
This gives us a 1000 x 400 matrix X where every row is a training example of a handwritten digit image. 
The second part of the training set is a 1000 x 1 dimensional vector y that contains labels for the training set
y = 0 if the image is of the digit 0, y = 1 if the image is of the digit 1.
This is a subset of the MNIST handwritten digit dataset (http://yann.lecun.com/exdb/mnist/)
