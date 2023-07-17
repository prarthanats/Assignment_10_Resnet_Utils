# Assignment_10_Resnet_Utils
Code to help with Data loading, Augmentation, Training of CIFAR10 Dataset

## Folder Structure

~~~
    config
    |── assignment_10.yaml
    data_loader
    |── data_augmentation.py
    |── data_loader.py
    utils
    |── ── helper.py
    |── ── learning_rate_finder.py
    |── ── visulatization.py
    model
    |── ── custom_resnet.py
    |── ── train_test.py
    |── README.md

~~~

### Config File
Includes the configurations for augmentations, training and learning rates. Augmentation is done using albumentations library.

### data_loader
Train & Test
Training and testing codes with options to input multiple optimizers, schedulers and loss criteria.

