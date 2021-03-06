# Attack on Image Classification Network

## This project works in two-stage:-
1. Classification of Image from ImageNet dataset using VGG-16 and Inception-V3.

2. Performing attack on the image (adding some perturbation to the original image so that the same model classify the image incorrectly)


## Prerequisites
Python, TensorFlow, Foolbox, Download ImageNet dataset.
Use Google Colab for running the project if you don't have high computing power.

## Source:-
https://arxiv.org/pdf/1801.00553.pdf

## Classification Model
Pre-trained model VGG16 and Inception-v3 for classification of an image from IMAGENET dataset.

## Attack
1. LBFGS Attack:-
This attack has been performed directly by importing LBFGS attack from foolbox library.

2. Iterative FGSM Attack:-
This attack has been performed by computed gradient iteratively to compute adversarial input.

3. PGD(Projected Gradient Descent) Attack:-
 This attack has been performed by iterative computation of gradient descent in such a way that the difference between given input and adversarial input always remains within a valid range
