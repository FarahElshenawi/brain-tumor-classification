# Brain Tumor Classification with CNN

This project is a **Convolutional Neural Network (CNN)** built from scratch using **PyTorch** to classify brain tumors from MRI images. It marks my first experience coding a CNN and using PyTorch, providing me with valuable insights into deep learning and computer vision.

## Project Overview

The primary goal of this project is to develop a CNN model that can accurately classify MRI images of brain tumors into four categories: 
- **No Tumor**
- **Pituitary**
- **Meningioma**
- **Glioma**

### Dataset

The dataset used for this project contains MRI images of brain tumors, labeled according to their respective categories. It is structured to facilitate the training and evaluation of the CNN model.

## Implementation

### Model Architecture

The CNN architecture consists of multiple convolutional layers followed by pooling layers, batch normalization, and fully connected layers to ensure effective feature extraction and classification.

### Training Process

The training process involved:
- Data preprocessing (resizing images and normalizing pixel values).
- Defining the loss function and optimizer.
- Training the model over several epochs while monitoring validation accuracy.

### Challenges Faced

1. **Model Overfitting**: Early on, the model exhibited signs of overfitting. Implementing dropout layers helped mitigate this issue and improve generalization.

2. **Hyperparameter Tuning**: Finding the right learning rate, batch size, and number of epochs was challenging. Iterative testing and monitoring the loss curve were crucial.

3. **Image Preprocessing**: Ensuring the images were appropriately resized and normalized was essential for achieving consistent results.

4. **Understanding PyTorch**: As a beginner with PyTorch, learning to implement the CNN architecture and understanding the library's functionalities posed initial challenges.

## Future Work

- Experimenting with data augmentation techniques to improve model robustness.
- Implementing transfer learning to leverage pre-trained models for better accuracy.
- Exploring ensemble methods to combine predictions from multiple models for improved performance.

