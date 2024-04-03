# Anomaly Detection

This project aims to apply unsupervised anomaly detection in computer vision to identify whether a testing image belongs to the same distribution as the training images. The model achieved a notable ROC_AUC score of **82.74%**.

## Task
Determining whether testing images share the same distribution as the training images.
![Out-of-Distribution Detection](https://github.com/Jingkang50/OODSurvey/blob/main/assets/benchmark.jpg)
[Source](https://github.com/Jingkang50/OODSurvey/blob/main)

## Model
The backbone of the model is the Autoencoder. The rationale behind using an autoencoder is that if the model can successfully reconstruct an image, then the image is considered 'normal'; otherwise, it is deemed an anomaly. In this project, various autoencoders including [fully connected network](https://github.com/L1aoXingyu/pytorch-beginner), [convolutional neural network](https://github.com/jellycsc/PyTorch-CIFAR-10-autoencoder/), [variational autoencoder](https://github.com/L1aoXingyu/pytorch-beginner), [ResNet](https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py), [OGNet](https://github.com/xaggi/OGNet) were employed for anomaly detection.

## Dataset
The [training set](https://drive.google.com/file/d/1SmJ8fnRS2I_XYRK-5fgFzA0u1uzI3kZ8/view?usp=sharing) and [testing set](https://drive.google.com/file/d/14NcWU31RzF0xjeZuzHOwX1I3wBUI6gEa/view?usp=sharing) are provided.

For detailed implementation and usage instructions, please refer to the provided [code](https://github.com/Dawson-ma/Anomaly-Detection/blob/main/Anomaly_Detection.ipynb).
