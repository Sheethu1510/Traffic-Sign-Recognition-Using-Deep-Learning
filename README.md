# Traffic Sign Recognition Using Deep Learning

## Overview

This project aims to classify traffic signs using deep learning techniques. Using image data from the German Traffic Sign Recognition Benchmark (GTSRB), a Convolutional Neural Network (CNN) model was developed to accurately recognize and categorize traffic signs into 43 distinct classes.

## Dataset

The GTSRB dataset contains over 50,000 images of traffic signs under various lighting conditions, angles, and resolutions. It is widely used for benchmarking image classification tasks in the domain of autonomous driving and road safety.

## Approach

* Performed image preprocessing including resizing and normalization.
* Visualized data to understand class distribution and variation.
* Split the data into training and test sets.
* Built and trained a custom CNN using TensorFlow/Keras.
* Evaluated model performance using accuracy metrics and confusion matrix.
* Visualized predictions to interpret model behavior.

## Key Technologies

* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn

## Outcome

The final model achieved high classification accuracy across most classes, showing strong potential for real-world applications in intelligent transportation systems and driver assistance technologies.

## Future Scope

* Test with real-time video input using a webcam.
* Apply transfer learning using pre-trained models for improved accuracy.
* Deploy the model for mobile or embedded applications.

