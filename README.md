# Boat Image Classification

## Introduction
The goal of this project is to train a classifier using LeNet architecture in order to classify different categories of boats navigating in the City of Venice (Italy).

The dataset that is being used here is the [MarDCT](http://www.dis.uniroma1.it/~labrococo/MAR/index.htm) from the Sapienza University of Rome.

The training dataset contains 4.774 images and the test dataset contains 1.969 from 24 different categories.

## Further improvements
In this project it was possible to have good results using the simplest classifier known, however it can be improved and achieve  much better results. Also, this training was most limited by the hardware being used, which do not allow to train with higher image sizes and more classes.

Another test that I would like to do is to use a pre-trained classifier, as the [VGG-16](http://www.robots.ox.ac.uk/~vgg/research/very_deep/), and retrain only the last layers in order to learn how to classify the boats in this dataset.

Besides this, it is also possible to improve the augmentation of the images (zoom, other transformations) and train each epoch with new augmented generated images.
