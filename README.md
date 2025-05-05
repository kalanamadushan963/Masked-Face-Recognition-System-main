# Masked-Face-Recognition-System
Masked-Face Recognition and detection system that can achieve real-time face recognition while wearing a facial mask.  

FaceNet technology with Inception-ResNet V1 convolutional neural networks has been used train the deep learning model using TensorFlow platform on a Python environment. CASIA-Webface and LFW datasets have been used for train and evaluation of the model. This program successfully identify faces with or without masks using SSD (Single-shot MultiBox Detector) and then recognize the faces in real-time by calculating the FaceNet embedding distance between anchor image and the images in the database.

