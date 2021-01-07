# Heart_Image_Analysis

# Purpose
This project was created to utilise TensorFlow, and aims to function as a simple CNN for the purpose of identifying injured and uninjured, stained, full-colour images of zebrafish hearts taken via confocal microscope. 

# Overview
The image input pipeline relies on images being stored locally by the user, and provisions are made to convert TIF images into PNGs which the later scripts are designed to handle. Noted at various points are sections where code may need to be altered to reflect the users file path where images are stored. 

Sections of code for defining and compiling the CNN and for testing the model on a validation dataset with permission from the author of the following code https://colab.research.google.com/github/milliams/intro_deep_learning/blob/master/mnist.ipynb .

At the head of the notebook is a list of the modeules that will need to be installed and imported for the script to run successfully. 

The dataset of images used to train and test this CNN are provided, already converted into png format. 

This CNN is not fully optimised for the specific images, although it functions failry well. As such, it may also be applicable to other biological images which display a difference in colouration. 

# Using This Code
In order to run this code on your machine:
1) Dowload the heart images and place in desired local environment, ensure folder organisational tips are followed as noted within the body of the code
2) Ensure required modules are installed and loaded. 
3) Modify sections of code relating to specific filepaths to reflect the users specific filepath.
4) Run the code in sequence (Note - conversino of image files to .png format can be skipped if using pre-supplied images), this code was written and tested in JupyterLab (https://jupyterlab.readthedocs.io/en/stable/) via the Anaconda launcher (https://docs.anaconda.com/).

# System Requirements
This code was designed and tested in Python 3.8.5, 07/01/2021.
The lowest specification hardware that was tested on are:
Processor: Intel Core i5-9300H @ 2.40G Hz 2.40 Hz.
RAM: 16GB.
It was not necessary to process the example images via a GPU, however if larger user-generated dataset are to be processed then performance may be impacted. 
