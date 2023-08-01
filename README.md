# Object-Localization-with-TensorFlow
This is a project on creating and training an Object Localization model with TensorFlow. Localization, in this context, means the position of the emojis in the images. This means that the network will have one input and two outputs. This task can be considered as a simpler version of Object Detection. In Object Detection, we might have multiple objects in the input images, and an object detection model predicts the classes as well as bounding boxes for all of those objects. In Object Localization, we are working with the assumption that there is just one object in any given image, and our CNN model will classify and localize that object.

*Objectives*:

1. Using TensorFlow's Keras API to create a convolutional neural network which will be trained to classify as well as localize emojis in images
2. Creating synthetic data for model training
3. Creating custom metrics and callbacks in Keras
4. Creating and training a multi output neural network to perform object localization

This implementation is a part of the course "Object Localization with TensorFlow" Course from Coursera
