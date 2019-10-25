
# Pytorch Dog Breed Detection

## Introduction
Welcome! This respository presents a notebook project focusing on dog breed classification using deeplearning and pytorch framework. The projetct is a requirement of the [udacity](https://udacity.com) pytorch deeplearning [nanodegree]([https://www.udacity.com/course/deep-learning-nanodegree--nd101](https://www.udacity.com/course/deep-learning-nanodegree--nd101)). 
If you are interested, you can find the original version of the notebook projects [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)

## Project Overview
Once more welcome to my solution of the [udacity](https://udacity.com) deeplearning with [pytorch](https://pytorch.org) nanodegree dog breed classification project. My entire solution can be found in [dog_app.ipynb](https://github.com/MbassiJaphet/pytorch-dog-breed-detection/blob/master/dog_app.ipynb).
The project makes use of Convolutional Neural Networks (CNN)  to detect as well as classifying canine breeds and [haarcascades](https://github.com/opencv/opencv/tree/master/data/haarcascades) from [OpenCV](https://opencv.org/) to detect human faces.
 ![dogs]
 ![dog]
 ![human]
Two approaches are implemented:
 * The first one, using a network designed from scratch.
 * The second one using transfer learning through finetuning of [VGG16]([https://neurohive.io/en/popular-networks/vgg16/](https://neurohive.io/en/popular-networks/vgg16/)) deep neural network pretrained on [ImageNet](http://www.image-net.org/) database.
 
## Requirements
 * [Pytorch](https://pytorch.org). (For this project I used pytorch 1.2)
 * [Human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).
 * [Dog dtaset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).
 * [OpenCV haarcascaes](https://github.com/opencv/opencv/tree/master/data/haarcascades)

## TODO
The following upgrades can be made on the actual project, cited in no particular order:

 - Turn the project in toa web app.
 - Overlay Snaptchat like filters on detected human heads
 - Add functionalities for dog mutts

[dogs]:https://raw.githubusercontent.com/MbassiJaphet/pytorch-dog-breed-detection/master/images/dogs.png
[dog]:https://raw.githubusercontent.com/MbassiJaphet/pytorch-dog-breed-detection/master/images/dog_detection.png
[human]:https://raw.githubusercontent.com/MbassiJaphet/pytorch-dog-breed-detection/master/images/human_dectection.png
