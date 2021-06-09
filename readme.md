## Introduction

This project aims to classify the emotion on a person's face into one of seven categories, using deep convolutional neural networks. The model is trained on the FER-2013 dataset which was published on International Conference on Machine Learning (ICML). This dataset consists of 35887 grayscale, 48x48 sized face images with seven emotions - angry, disgusted, fearful, happy, neutral, sad and surprised.

## Algorithm

- First, the haar cascade method is used to detect faces in each frame of the webcam feed.
- The region of image containing the face is resized to 48x48 and is passed as input to the CNN.
- The network outputs a list of softmax scores for the seven classes of emotions.
- The emotion with maximum score is displayed on the screen.

## Folders with class names mapped to numbers for ease

- 0--angry
- 1--disgust
- 2--fear
- 3--happy
- 4--neutral
- 5--sad
- 6--surprise
