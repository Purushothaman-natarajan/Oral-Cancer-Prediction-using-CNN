# Oral Cancer Prediction using Transfer Learning on CNN

This repository focuses on utilizing Convolutional Neural Networks (CNNs) with transfer learning for the prediction of oral cancer. Here, we employ pre-trained CNN models such as VGG16, VGG19, ResNet50, InceptionV3, DenseNet121, MobileNetV2, Xception, and InceptionResNetV2.

## Models Utilized

The project harnesses the power of various pre-trained models:

- VGG16
- VGG19
- ResNet50
- InceptionV3
- DenseNet121
- MobileNetV2
- Xception
- InceptionResNetV2

## Customization and Training Strategy

Each base model undergoes a process of customization to tailor it for oral cancer prediction:

1. **Flattening**: The output is flattened to prepare for fully connected layers.
2. **Fully Connected Layer Addition**: A dense layer with 1024 neurons and ReLU activation is added.
3. **Output Layer Creation**: Finally, an output layer with 2 neurons and softmax activation is appended for binary classification (Normal or OSCC).

These custom models are then trained and evaluated, producing the following performance metrics:
<div align="center">
  
|       Model         | Accuracy | Epochs |
|:-------------------:|:--------:|:------:|
|       VGG16         | 0.956667 |   17   |
|       VGG19         | 0.946000 |    7   |
|      ResNet50       | 0.806000 |   30   |
|    InceptionV3      | 0.957333 |    8   |
|    DenseNet121      | 0.975333 |   33   |
|    MobileNetV2      | 0.969333 |   30   |
|      Xception       | 0.966000 |   37   |
| InceptionResNetV2   | 0.954667 |    4   |

</div align="center">

## Exploring the Code

For an in-depth exploration of the codebase and its implementation, we highly recommend referring to the [notebook file](https://github.com/Purushothaman-natarajan/Oral-Cancer-Prediction-using-CNN/blob/main/Cancer_Prediction_(Development_and_Testing).ipynb) provided within this repository. This notebook offers comprehensive insights into the development and testing phases of the project.

##### Trained models and the processed data is uploaded via drive [Link]()

## Acknowledgements

If you find this project beneficial for your research or work, we kindly request citing this repository. Your support is greatly appreciated. Thank you for your interest and contribution to advancing cancer prediction methodologies.
