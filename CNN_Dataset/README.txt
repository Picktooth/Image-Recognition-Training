This folder contains images from the CIFAR10 dataset with applied gaussian noise.
Intended to be used to train a model through an iterative process by progressively introducing noisier images through each stage. 

Starting with the original CIFAR10 dataset to obtain the baseline model. This baseline will then be retrained on higher difficulty images (more noise) or combined with separate models trained on the varying levels of noisy images.

This entire dataset is split into 4 levels:

   - Level 0 (Baseline): Model trained using the original CIFAR10 dataset
   - Level 1: Model trained on subset of the CIFAR10 dataset with gaussian noise applied at a .008 variance
   - Level 2: Model trained on subset of the CIFAR10 dataset with gaussian noise applied at a .02 variance
   - Level 3: Model trained on subset of the CIFAR10 dataset with gaussian noise applied at a .05 variance

The training image sets for levels 1 - 3 each contain 25000 images with 2500 images per class (Half of the original CIFAR10 training data)
Models should be trained using the standard train, validate, and test process