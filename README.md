# License-Plate-Detection-Indentification

This is a two stage lightweight and robust license plate recognition based on SSD and LPRNet and implemented Tensorflow.
SSD is a very well-known real-time single-step object detector model and it is trained for license plate detection.
LPRNet, another real-time end-to-end DNN, is utilized for the subsquent recognition.
This network is attributed by its superior performance with low computational cost without preliminary character segmentation.
It's an interesting approach that performs character recognition without any use of RNNs (just a CNN + a decoder).

#In depth explanation of each step
The approach is divided into 2 steps: detection of the plate and recogition of the text.
The scripts to perform each step are separated into the two folders "lp_recognition" and "lp_detection".
An in-depth explanation is provided in order to use these two algorithms properly:

License Plate Detection
License Plate Recognition

The Jupyter Notebook Tutorial unifies both steps in a full pipeline.
There is also a pdf in two folders "lp_recognition" and "lp_detection" expaining the structure.
The code is based on two gibhub repositories, check them to have more information:

Tensorflow API for Object Detection
Intel Openvino training extension - License Plate Recognition
