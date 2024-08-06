# Lung Cancer Classification

## Project Description

This project aims to classify different types of lung cancer using deep learning techniques. The dataset includes images of various types of lung cancer and normal lung tissues. The primary goal is to develop a model that can accurately distinguish between different classes of lung cancer.

## Dataset Information

The dataset used in this project consists of images categorized into the following classes:
- Colon Adenocarcinoma (colon_aca)
- Normal Colon (colon_n)
- Lung Adenocarcinoma (lung_aca)
- Normal Lung (lung_n)
- Lung Squamous Cell Carcinoma (lung_scc)

The images are stored in directories named according to their classes.

## Installation and Setup

To run this project, you need to have the following libraries installed:


pip install numpy pandas matplotlib scikit-learn tensorflow keras opencv-python pillow

## Usage

1. **Data Preparation:**. The path to the dataset in the code is `C:\\Users\\rahul\\Downloads\\archive`.

2. **Run the Jupyter Notebook:**
   - Open `Lung_cancer.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Execute the cells sequentially to preprocess the data, build and train the model, and evaluate its performance.

## Model and Training

The project utilizes Convolutional Neural Networks (CNNs) for image classification. The model is built using TensorFlow and Keras libraries. The training involves splitting the dataset into training and testing sets and applying various image preprocessing techniques.

## Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and ROC curves are also used for a comprehensive evaluation.

## Results

The results of the model, including accuracy and confusion matrices, are displayed in the notebook. The model demonstrates a high level of accuracy in classifying different types of lung cancer.
