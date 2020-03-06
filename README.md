# Image Caption Generator

In this Python project, I implemented the caption generator using CNN (Convolutional Neural Networks) and LSTM (Long short term memory). The image features were extracted from Xception which is a CNN model trained on the imagenet dataset and then we feed the features into the LSTM model which will be responsible for generating the image captions.

## Dataset used:
Flickr_8k dataset, which is easily availabel online was used for building the model. It is a dataset containing 8000 images and contains a token file containing Image name with their respective caption.

## The Model:
The model which was made is also called CNN-RNN model.
+ CNN is used for extracting features from the image. We will use the pre-trained model Xception.
+ LSTM will use the information from CNN to help generate a description of the image.

The final model looks like: 
![model](https://github.com/Yashpd/Image_Caption_Generator/blob/master/model.png)
