# Brain-Tumor-Detection-using-CNN
This repository contains the implementation of brain tumor detection using Convolutional Neural Networks (CNN). Two models have been employed for this task: EfficientNet and a custom-built CNN. The dataset used for training and testing the models is included in the repository.

# Dataset
The dataset used for training and evaluation is provided in the dataset directory. It contains MRI images of brain tumors along with their corresponding labels indicating the presence or absence of a tumor.

# Models
1. EfficientNet: 
EfficientNet is a scalable and efficient convolutional neural network architecture that has shown remarkable performance across various image classification tasks. We employ a pre-trained version of EfficientNet and fine-tune it on our brain tumor dataset.

2. Custom CNN: 
In addition to EfficientNet, we design a custom CNN architecture tailored specifically for brain tumor detection. The architecture is defined in the custom_model.py file.

# Acknowledgments
The dataset used in this project is obtained from [https://www.kaggle.com/datasets/abhranta/brain-tumor-detection-mri] .
The implementation of EfficientNet utilizes the EfficientNet-PyTorch library.
