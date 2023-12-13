# Deep Learning Project 
- COVID-19 Diagnosis Based On Deep Learning On Radiological Imaging
# Specific Aim
This is a repository for the Deep Learning (CSCI 7850) semester project. The project aims to use deep learning methods to analyze COVID-19 X-ray images. The dataset in the code in this repository is a small subset of the COVID-19 dataset from Kaggle, and its source URL is "https://www.kaggle.com/datasets/tawsifurrahman/covid19- radiography- database/data". The images will be resized into (224,224,3). This study aims to detect and classify COVID-19 cases using deep convolutional neural networks, including ResNet50, ResNet101, CheXNet101, and CheXNet201, combined with image augmentation techniques. In addition, we will compare the impact of using different nonlinear activation functions such as ReLU and GELU on model performance. All of the models will load the pre-trained weights here. The accuracy and other metrics will be printed after each model.
# Instructions
This repository contains  procedures, all the model architecture, and their pre-trained weights.
To clone the repository and run the notebook please execute the below Git command.
```sh
[git clone](https://github.com/yizhou95/DeepLearning.git) https://github.com/yizhou95/DeepLearning.git
```
  
The deployment notebook is divided into several sections as below:
* Library
* URLs
* Download Sample Dataset
* Read sample dataset from the Covid19DatasetSample directory
* Use URLs to get pre-trained weights
* Each Model
* Evaluate the model

The dataset URL is available as below:
https://yizhoubucket.s3.us-east-2.amazonaws.com/Covid19DatasetSample.zip

The weights URLs are available as below:
* https://yizhoubucket.s3.us-east-2.amazonaws.com/resnet50_weights.pth
* https://yizhoubucket.s3.us-east-2.amazonaws.com/resnet50_gelu__weights.pth
* https://yizhoubucket.s3.us-east-2.amazonaws.com/resnet101_weights.pth
* https://yizhoubucket.s3.us-east-2.amazonaws.com/resnet101_gelu__weights.pth
* https://yizhoubucket.s3.us-east-2.amazonaws.com/chexnet_weights.pth
* https://yizhoubucket.s3.us-east-2.amazonaws.com/chexnet_gelu_weights.pth
* https://yizhoubucket.s3.us-east-2.amazonaws.com/chexnet201_weights.pth
* https://yizhoubucket.s3.us-east-2.amazonaws.com/chexnet201_gelu_weights.pth


