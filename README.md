# Traffic-Light-Recognition-using-CNN
A traffic sign recognition project using the GTSRB dataset, involving CNN design, data preprocessing, training, and testing, aimed at applications in autonomous driving.

# Project Overview
Objective: To develop a convolutional neural network (CNN) model capable of accurately classifying different types of traffic signs from images.

Dataset: The GTSRB dataset, which includes images of various traffic signs captured under different conditions. The dataset was obtained from Kaggle and consists of training, validation, and test sets.

# Steps Involved:

1- Data Preprocessing: Loaded and preprocessed the dataset by resizing the images, normalizing pixel values, and applying data augmentation techniques to enhance the model's robustness.
2- Model Design: Developed a CNN architecture tailored for image classification tasks. The model was designed to balance complexity with performance.
3- Training and Validation: Trained the model on the preprocessed dataset, with a split between training and validation data to monitor performance and avoid overfitting.
4- Testing: Evaluated the model using the test dataset and calculated the accuracy to measure its effectiveness.
5- Single Image Prediction: Implemented a script to allow for the testing of individual images, providing a flexible way to validate the model's predictions outside of the dataset context.

# Technologies Used:

Python
Keras/TensorFlow for model development
OpenCV and PIL for image processing
NumPy and Pandas for data manipulation
Matplotlib for result visualization
