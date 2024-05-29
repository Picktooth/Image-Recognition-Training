This folder contains files for when I started practicing training image recognition models using neural networks.

There are three code files:

Train: Code for training models using Kfold validation and cross-validation
Kfold Model Stack.ipynb: Creating a new model by stacking previous models
Normal to Gaussian Noise.ipynb: Applying gaussian noise to images

This project also contains a couple folders to mention:

CNN_Dataset: This folder contained images from the CIFAR10 dataset with applied gaussian noise. A separate README is there to describe its purpose. (Images have been removed due to upload limits)

Models: Holds the current best performing models. Also holds backups for those models and older models I trained.

Noiseimg: Contained both training and test images. Project is currently set up to use image sets from the CNN_Dataset folder for training and the image set from Noiseimg for testing. (Images have been removed due to upload limits)

Notebooks: Contains the very first files I created. Current files are built off of these so they're no longer necessary. I just have them here as a fallback

Results: Holds model accuracy results on test set and model weights

The environtment can be obtained by importing the ImgRecTrain.yaml file
