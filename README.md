# MNIST-Digit-Classification

### Introduction:
If you have written Machine Learning enthusiast in your bio and had taken some MOOC course for introduction to neural networks and deep learning then I can bet you must have solve this problem. Ok jokes apart this is a classification task in which we have 28 x 28 grayscale images of digits which are handwritten from 0 to 9. Our task is to develop a model which can recognize digits.

First of all I would like to explain why we need a Neural Network to get a high performance models.
In real life we deal with images of size 30 x 360 or 480 x 480 or may be high resolution images like 1080 x 1080 size then the feature vector explodes to millions and if we will use them it to train a Logistic regression we won't be able to learn a complex model as the feature vector is quite high.

Here comes Neural Networks in handy which allows us to learn non-linear complex models which are well suited and proved to be state of the art models for not only  computer vision task but in NLP, time-series predictions and many other.

### Approach:
After visualization of some images using the Matplotlib library of python and analyzing the distribution of the data across the 10 classes using seaborn library. I trained a Logistic Regression model and SVM classifier  with a Multi Class Classification approach.

**Logistic Regression:**
* Train Accuracy - 95%
* Validation Accuracy - 91%

**SVM:**
* Train Accuracy - 98%
* Validation Accuracy - 92%

Which implies that we are facing overfitting problem in both of the model. Then I trained a two layers deep neural networks with 256 hidden unit in each to achieve:
* Train Accuracy - 97.5%
* Validation Accuracy - 97%

And over this by using the CNN I achieved:
* Train Accuracy - 99.5%
* Validation Accuracy - 99%

So, that's is all about MNIST Digit Classification task. If you face problem here then do check ou my <a href ='https://www.kaggle.com/code/abhishek123maurya/digit-classifiers/'>notebook<a/> on Kaggle.
