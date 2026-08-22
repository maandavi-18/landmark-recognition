# Landmark Recognition Using Deep Learning

A deep learning-based image classification project for recognizing landmarks from images using **TensorFlow** and **transfer learning**.

## Project Overview

The objective of this project is to build a deep learning model capable of recognizing and classifying landmarks from images. The project involves preparing image data, organizing it into training, validation, and testing sets, and training a neural network using transfer learning.

## Features

* Image-based landmark classification
* Large-scale image dataset handling
* Image preprocessing and data preparation
* Training and validation pipeline
* Transfer learning for feature extraction
* Model performance evaluation

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Computer Vision

## Dataset

This project uses a landmark image dataset containing images associated with different landmark classes.

The complete dataset is not included in this repository due to its large size.

The notebook expects the dataset files to be organized locally before training.

## Project Workflow

1. Load the training and testing metadata.
2. Select and organize landmark classes.
3. Download and prepare the corresponding images.
4. Split the data into training, validation, and testing sets.
5. Preprocess and resize images.
6. Apply transfer learning to extract image features.
7. Train the classification model.
8. Evaluate the model using validation performance.

## Results

The model was trained on a large landmark image dataset and evaluated using validation data. Training performance improved progressively, with validation accuracy reaching the **70%+ range** in the training results available in the notebook.

## Repository Structure

```text
landmark-recognition/
│
├── Landmark_Recognition.ipynb
├── README.md
├── .gitignore
└── LICENSE
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/maandavi-18/landmark-recognition.git
```

2. Install the required libraries:

```bash
pip install tensorflow numpy pandas matplotlib requests
```

3. Organize the dataset according to the paths used in the notebook.

4. Open and run:

```text
Landmark_Recognition.ipynb
```

## Future Improvements

* Improve model accuracy using additional fine-tuning.
* Use modern TensorFlow/Keras APIs.
* Add data augmentation.
* Create a user-friendly interface for landmark prediction.
* Deploy the trained model as a web application.

## Author

**Maandavi Srivastava**

Electronics and Communication Engineering Student
Interested in Software Development, Artificial Intelligence, Machine Learning, and Computer Vision.

