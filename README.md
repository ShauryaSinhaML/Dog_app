# Dog_app

# Files:
- <b>project_blog.pages :</b> Contains A Blog Post abt the project
- <b> dog_app (1).ipyb :</b> Contains the code for this project
  
## Problem Statement¶

Given an image of a dog, our algorithm should identify an estimate of the canine’s breed. If supplied an image of a human, the code should identify the resembling dog breed.

## Datasets and Inputs¶

We will be using 2 datases that have been provided by udacity and can be found in the workspace diectly:
Download the dog dataset. Unzip the folder and place it in this project’s home directory, at the location /dog_images.
There are 8351 total dog images and 133 distinct breeds of dogs.
Download the human dataset. Unzip the folder and place it in the home directory, at location /lfw.
There are 13233 total human images.
We will be utilizing these 2 datasets for the pupose of out Problem statement.



## Solution Statement¶

In this project we are going to use Tensorflow to create our classifier Tensorflow is an open-source machine learning library for Python, based on Torch, used for applications such as natural language processing. It is primarily developed by Facebook’s artificial-intelligence research group, and Uber’s “Pyro” Probabilistic programming language software is built on it.
We will be Using CNN and Transfer Learning to implement the classifier the details of both of them can found above.

## Benchmark Model:¶

We will be using the CNN model created from Scratch as our Bechmark Model that will provide us a space for improvement and see the effectiveness of tranferlearning at a much clearer scence.


Evaluation Metrics:¶

We will be using Test Loss and Test Accuracy of the model on the Test Dog Images datase for both the models benchmark and ResNet50 to compare them.
Loss is the result of a bad prediction. A loss is a number indicating how bad the model's prediction was on a single example. So test loss is Loss on the Test dataset.
Accuracy is the number of correctly predicted data points out of all the data points, So test Accuracy is the Accuracy of the model on test dataset.

## Project Design:¶

Process to be followed:
- Find the right dataset - Human dataset and Dog Dataset specified above
- Import the dataset and preprocess it(if required) - data augumentation, cropping, padding, etc
- Detect Humans
- Detect Dogs
- Create a CNN model from scratch of our own to classify Dog Breed
- Create a CNN model by using Transfer Learning to classify Dog Breed - ResNet50 / VGG16 / etc
- Test both the models

## Results:
- The First Model (from Sratch) Test acc. = 1.0766%
- Second Model (VGG-16) Test acc. = 40.1914%
- Thisr Model (Resnet-50) our Test acc. = 81.1004784689%

## Resources:¶

- Research paper for Deep residual learning.
- VGG-19 by Aakash Kaushik (opengenus).
- Floating point operations per second (FLOPS) of Machine Learning models.
- Convolutional Neural Network by Piyush Mishra and Junaid N Z (OpenGenus)
- https://github.com/vdumoulin/conv_arithmetic
- https://deepai.org/machine-learning-glossary-and-terms/accuracy-error-rate
- https://intellipaat.com/community/368/how-to-interpret-loss-and-accuracy-for-a-machine-learning-model
- Udacity Workspace for Dog Preed Classification.
- Resnet-50 by Aakash Kaushik (opengenus).
