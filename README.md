# Brain_Tumer_detection
Brain Tumor Detection Using CNN
Project Overview:
This project uses a Convolutional Neural Network (CNN) to classify brain MRI images into two categories: Tumor (Yes) and No Tumor (No). 

The model is trained on MRI images to predict the presence of a brain tumor.


Dataset:
Yes: Images of brain MRIs with tumors (yes)/


No: Images of brain MRIs without tumors /no)
Images are resized to 128x128 pixels for uniformity.
Data is normalized to improve model performance.



Steps:
Data Loading and Preprocessing:
Load images from the dataset.
Resize all images to 128x128.
Normalize pixel values (range: 0-1).
Create labels: 0 for healthy, 1 for tumor.

Data Splitting:
Split data into training (80%) and validation (20%) sets.
Model Architecture:

Convolutional and pooling layers for feature extraction.
Fully connected layers for classification.
Sigmoid activation for binary output.
Training:

Optimizer: Adam.
Loss: Binary Crossentropy.
Metrics: Accuracy.
Evaluation and Visualization:

Classification report for performance metrics.
Confusion matrix to visualize predictions.
Accuracy and loss graphs.
Display misclassified images.

Results
Metrics:
Validation accuracy and loss are reported after training.
Performance is visualized with graphs and a confusion matrix.

Requirements:-
Python
TensorFlow/Keras
NumPy
OpenCV
Matplotlib
Seaborn
Pandas
scikit-learn
