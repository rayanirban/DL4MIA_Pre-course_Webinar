# EMBO-DL4MIA Pre-course exercises and materials

## Schedule:

- Webinar 1: April 15   
- Webinar 2: April 29 
- Webinar 3: May 3

## setup
Run the notebooks on Collab

webinar 1 - Discuss anything but mainly focusing on notebooks 1 and 2
webinar 2 - Discuss anything but mainly focus on notebooks 2 and 3
webinar 3 - Anything Optional (if required)

# Exercises for Webinar 1

The exercise for the first webinar will refresh your image analysis knowledge and teach basic image analysis methods in python with scikit-image.
Please finish the following exercise before the first webinar:
- `image_analysis.ipynb`: image analysis refresher on data from the Kaggle Data Science Bowl for nucleus segmentation. 

If you are familiar with image analysis with scikit-image already you can also skip this exercise.
If you are unfamiliar with image analysis or python in general, please check out the additional materials below. 

## Additional materials:
 
### Introductions to image analysis for biology (ibiology videos)
 * [Introduction to Bioimage Analysis](https://www.ibiology.org/techniques/introduction-to-bioimage-analysis/)
 * [Bioimage Analysis](https://www.ibiology.org/techniques/bioimage-analysis/)

### Bioimage analysis with python and jupyter (neubias webinar)
* [part 1](https://www.youtube.com/watch?v=2KF8vBrp3Zw&t=0s)
* [part 2](https://www.youtube.com/watch?v=Y3pB3wnOivE&t=0s)
* [Q&A](https://forum.image.sc/t/neubias-academy-home-webinar-interactive-bioimage-analysis-with-python-and-jupyter-questions-answers/37596)
* [slides](https://docs.google.com/presentation/d/1N1ikhtEscuviINAnqUXnUSRS-Gz9sp-0bX8IO_ecW3E/edit)
* [notebooks](https://github.com/guiwitz/neubias_academy_biapy)

### Introductions to python and data science in python
 * [Tutorial: Basic Python](https://www.w3schools.com/python/)
 * [Python for Data Science and AI](https://www.coursera.org/learn/python-for-applied-data-science-ai) - basic
 * [Python 3 Programming Specialization](https://www.coursera.org/specializations/python-3-programming) - different levels 
 * [Python for science](https://scipy-lectures.org/intro/index.html) - lecture notes, useful to walk through

### Image analysis with python and scikit-image
 * [Tutorial: Image processing with Python](https://datacarpentry.org/image-processing/)
 * [Skimage examples](https://scikit-image.org/docs/stable/auto_examples/index.html)
 * [Python image manipulation tools](https://opensource.com/article/19/3/python-image-manipulation-tools)


 # Exercises for Webinar 2

We provide exercises for pytorch and keras.

## Pytorch

Exercises for Image Classification with pytorch. Contains the following exercises:
- `pytorch/1_data_preparation`: pytorch dataloader for classification. 
- `pytorch/2_logistic_regression`: image classification with a simple logistic regression model. 
- `pytorch/3_multi_layer_perceptron`: image classification with a multi-layer perceptron. 

All the exercises use the [CIFAR10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html).
For the pytorch exercises, please use the `DL Course(Pytorch)` environment in BAND. You can start it via `Applications->Programming->DL Course(Pytorch)`.

## tensorflow/keras

Here we will perform a simple classification task that will show you the basics of using tensorflow/keras.  

- `keras/classification_simple_keras.ipynb`: Basic demonstration of a feature classification example with a Multi layer perceptron (MLP) using tensorflow/keras

For the keras exercises, please use the `DL Course(Keras)` environment in BAND. You can start it via `Applications->Programming->DL Course(Keras)`.

## Content

These exercises will cover basic machine learning and computer vision concepts relevant for image classification.
You can find lectute notes recapping these contents ([here](https://docs.google.com/presentation/d/1PNoyDIemKKE7Eo02txJfY0kge7tqlrWB1EY9USK4OGY/edit?usp=sharing)), covering:

- Machine Learning Basics
    - Supervised Learning
    - Artificial Neural Networks
    - Stochastic Gradient Descent
- Computer Vision Basics
    - Tasks: Image Classification, Object Detection and Segmentation
    - Computer vision with preset features and shallow learning
    - Preview of feature learning and CNNs
- Deep Learning Frameworks
    - Why do we need deep learning frameworks?
    - Overview of the popular frameworks
    - Introduction to pytorch

There are also video recordings from an EMBL course on these topics:
- [Video 1](https://www.youtube.com/watch?v=-TDNDv2C6ow&feature=em-share_video_user)
- [Video 2](https://www.youtube.com/watch?v=-RmipXviG8E&feature=em-share_video_user)
- [Video 3](https://www.youtube.com/watch?v=_dNc7odIRiM&feature=em-share_video_user)
- [Video 4](https://www.youtube.com/watch?v=-hHtfd9JrAg&feature=em-share_video_user)

And there are lots of other related materials available online, for example:

### Pytorch
 * [Building networks from torch primitives](https://pytorch.org/tutorials/beginner/nn_tutorial.html)
