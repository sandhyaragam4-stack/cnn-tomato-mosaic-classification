# cnn-tomato-mosaic-classification
# Tomato Mosaic Virus Detection using CNN
This project focuses on identifying Tomato Mosaic Virus infected leaves using a Convolutional Neural Network (CNN) model built with TensorFlow/Keras. The model was trained on tomato leaf images from the PlantVillage dataset and compared using preprocessing and augmentation techniques.

## Objective
The main aim of this project is to classify tomato leaves into:
- Tomato Mosaic Virus
- Healthy Tomato Leaves

The project was done to understand how deep learning can be applied in agricultural disease detection and image classification problems.


## Dataset Used

Dataset: PlantVillage Dataset
Classes used in this project:
- Tomato__Tomato_mosaic_virus
- Tomato_healthy

The dataset contains leaf images collected under controlled conditions for plant disease identification.


## Tools and Libraries
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab


## Deep Learning Techniques Used
- Convolutional Neural Networks (CNN)
- Image Augmentation
- Batch Normalization
- Dropout Layers
- Adam Optimizer

## Data Preprocessing
The following preprocessing steps were used:
- Image resizing
- Rescaling pixel values
- Data augmentation for training images
- Train-validation split

Augmentation techniques included:
- Rotation
- Zoom
- Horizontal flipping
- Shearing

## Model Architecture
The CNN model consists of:
- Convolution layers
- MaxPooling layers
- Batch Normalization
- Dropout
- Dense layers
- Softmax output layer

## Results
### Validation Accuracy
95.4%

### Classification Report
| Class | Precision | Recall | F1-Score |
| Tomato Mosaic Virus | 1.00 | 0.76 | 0.86 |
| Healthy Tomato Leaf | 0.95 | 1.00 | 0.97 |
Overall Accuracy: 95%

## Observations
- The model achieved high validation accuracy on the dataset.
- Data augmentation helped improve generalization.
- Some fluctuations in validation loss were observed due to overfitting in later epochs.
- The model performed better on healthy leaves compared to diseased leaves because of class imbalance.


## Future Improvements
- Train on larger field datasets
- Use transfer learning models like ResNet or EfficientNet
- Improve class balance
- Deploy as a web/mobile application for farmers

## Output
The trained model was saved after training and can be used for prediction on new tomato leaf images.
