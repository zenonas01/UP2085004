# CNN Models for Image Classification

This README provides an overview of the CNN models implemented for image classification. The code is available in the `cnn_models.ipynb` notebook.

## Introduction

The provided code implements several Convolutional Neural Network (CNN) models for image classification tasks. It utilizes TensorFlow and Keras libraries for building and training the models.

## Usage

1. **Setup**: Mount Google Drive and extract the dataset.
2. **Data Exploration**: Display unique resolutions and visualize the number of images available for each class.
3. **Data Preprocessing**: Prepare the dataset for training and validation by resizing images and splitting into batches.
4. **Model Training**: Train each CNN model for a specified number of epochs using the training and validation datasets.
5. **Evaluation**: Evaluate the performance of each model using the validation dataset and compare their accuracy and error rates.
6. **Conclusion**: Discuss the results and insights gained from training and evaluating the models.

## Models Implemented

The following CNN models are implemented and trained for image classification:

- **Custom CNN**
- **VGG16**
- **VGG19**
- **DenseNet**
- **Xception**
- **MobileNet**
- **ResNet**

For each model, the training process includes compiling the model, defining callbacks for model checkpoints and learning rate scheduling, training the model using the training and validation datasets, and saving the trained model.

## Evaluation and Comparison

The performance of each model is evaluated based on accuracy and error rates. The results are visualized using bar charts to compare the models' performance.

## Conclusion

The README provides an overview of the CNN models implemented for image classification. It outlines the steps to use the provided code and summarizes the key findings from training and evaluating the models.

