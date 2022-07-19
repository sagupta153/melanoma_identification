# Melanoma Identification using CNN - Assignment - by Sankalp Gupta
> This assignment is about image classification to classify melanoma related images into 9 different kinds of melanomas (skin cancers)

## Table of Contents
* [General Info](#general-information)
* [CNN Modelling](#cnn-modelling)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
> Assignment Obective: To build an advanced Convolutional Neural Network (CNN) model, to classify images
> Data-set: Containing Train and Test sets totalling 2357 images, divided into 9 classes
> Each image is an RGB image of size 180 x 180
> The model was executed using Google Colab to take advantage of the GPU processor provided free by Google

## CNN Modelling
> The modelling process involved the following steps
1. Connecting the image data files stored on github to Google Colab
2. Loading the image data files into the keras utility image_dataset_from_directory
3. Visualizing sample images from the dataset
4. Visualizing class imbalance
5. Creating and testing different CNN models.
6. The models started with 64 output features, followed by 128 and 256, and finally a dense layer of 512 neurons
7. The models differed in the use of batch normalization, dropouts, LC2 regularizer, number of epochs, etc.

## Conclusions
> Following conclusions can be made from the modelling process
 1. Slightly more than 50% validation accuracy was achieved
 2. As the number of epochs increased, validation accuracy remained the same, but training accuracy kept on increasing. This indicates increasing over-fitting
 3. On average, about 20 epochs were sufficient
 4. Use of augmentor to increase the data size from 2357 images to 4500 images was done
 5. However, the above change did not result in any significant increase in accuracy
 6. Accuracy on test dataset, was very low. About 34%. Clearly a lot more needs to be done to train the CNN to perform reliably

## Technologies Used
- operating system - microsoft windows - version Windows 11 Home edition
- programming language - python 3 - version 3.9.7 
- jupyter notebook - version 6.4.5
- numpy library - version 1.20.3
- matplotlib library - version 3.4.3
- tensorflow library - version 2.9.1
- keras library - version 2.9.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Convolutional Neural Network Assignment in Deep Learning course
- References : Convolutional Neural Network Assignment, Module-6, Deep Learning, as a part of PG course in AI & ML by IIITB and upGrad
- This project was based on [Deep Learning](https://learn.upgrad.com/course/1994/segment/13375/109590/331557/1723023).


## Contact
Created by [@sagupta153] - feel free to contact me!