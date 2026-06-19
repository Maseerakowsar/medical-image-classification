# Medical Image Classification using CNN

## Project Overview

This project focuses on Medical Image Classification using Deep Learning. A Convolutional Neural Network (CNN) is trained to classify Chest X-ray images into two categories:

* Normal
* Pneumonia

The objective of this project is to assist in the early detection of pneumonia by analyzing medical images automatically.

## Dataset

The project uses the Chest X-ray Pneumonia Dataset.

Dataset Classes:

* NORMAL
* PNEUMONIA

The dataset contains training and testing images of chest X-rays used for model training and evaluation.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

## Methodology

1. Load and preprocess chest X-ray images.
2. Resize images to a fixed size.
3. Normalize pixel values using ImageDataGenerator.
4. Build a Convolutional Neural Network (CNN).
5. Train the model using the training dataset.
6. Evaluate the model using the test dataset.
7. Generate accuracy and loss graphs.
8. Save the trained model.

## CNN Architecture

The CNN model consists of:

* Convolution Layer (32 filters)
* Max Pooling Layer
* Convolution Layer (64 filters)
* Max Pooling Layer
* Flatten Layer
* Dense Layer (128 neurons)
* Output Layer (Sigmoid Activation)

## Results

Training Accuracy: 98.5%

Test Accuracy: 75%

The model successfully classifies chest X-ray images into Normal and Pneumonia categories.

## Project Structure

Medical_Image_Classification/

├── dataset/

├── notebooks/

│ └── medical_image_classification.ipynb

├── models/

│ └── medical_image_model.h5

├── screenshots/

├── README.md

## Future Improvements

* Use larger medical datasets.
* Apply data augmentation techniques.
* Improve model accuracy using advanced CNN architectures.
* Deploy the model as a web application.

## Conclusion

This project demonstrates the application of Deep Learning and Convolutional Neural Networks for medical image classification. The trained model can classify chest X-ray images and assist in pneumonia detection with a test accuracy of 75%.

## Author

Maseera Kowsar
