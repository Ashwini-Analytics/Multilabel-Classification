# Multilabel-Classification
Satellite Images of Amazon rainforest - Planet dataset

## Introduction:
Nowadays data is unstructured and is categorized into multiple labels. For example, shopping
data, a consumer can purchase products from different categories from the same store or the
consumer can purchase it from different store at the same time. So I thought it will be useful if I
work on such dataset. Classification on such data I known as Multi-label Classification. The
dataset that I worked on is a planet dataset on Satellite image of Amazon Forest. There are
small squares of satellite images taken from space of the Amazon rainforest in Brazil in terms of
17 classes, such as water, clear and agriculture. The color images were provided in both TIFF
and JPEG format with the size 256×256 pixels. A total of 40,779 images were provided in the
training dataset and 40,669 images were provided in the test set for which predictions were
required.

## Problem Statement:
It is to classify the images into 17 labels using multi label classification method. By this, one
would know the percentage of land left for agriculture, water, or any of thier personal interest.

## Modelling and Evaluation:
I have used a CNN model, a baseline model with a VGG-type structure. That is blocks of
convolutional layers with small 3×3 filters followed by a max pooling layer, with this pattern
repeating with a doubling in the number of filters with each block added. And a sigmoid
function for the output. The model was able to score 0.754 of F-beta value (beta = 2) and loss of
0.182.

## Future Work:
The future work consists of using a transfer learning on the model. And using the available
weights to better train and predict the model.


###### This project is inspried by jason brownlee's post on machine learning mastery- https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-to-classify-satellite-photos-of-the-amazon-rainforest/
