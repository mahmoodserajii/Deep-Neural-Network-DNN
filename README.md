# **Fashion MNIST Classification with DNN**

## **Overview**
This project contains a complete, end-to-end machine learning pipeline using a **Deep Neural Network (DNN)** to classify fashion items from the **Fashion MNIST dataset**. The pipeline demonstrates best practices for data handling, model training, and performance evaluation in a self-contained Python script.

## **Datasets**
* **Fashion MNIST** – A dataset of 60,000 training images and 10,000 test images of fashion articles (e.g., shirts, trousers, bags).

## **Features**
* **Data Loading and Preprocessing:** Handles data loading, normalization, and reshaping.
* **Model Building:** Constructs a sequential DNN model with multiple dense layers.
* **Model Training:** Trains the model using a validation set and an `EarlyStopping` callback to prevent overfitting.
* **Performance Evaluation:** Reports key metrics including accuracy, precision, recall, and F1-score.
* **Visualization:** Generates plots for training/validation accuracy and loss over epochs.
* **Confusion Matrix Analysis:** Provides a detailed breakdown of model errors.

## **File**
* `dnn.ipynb` – Contains the complete Python script for the entire pipeline.

## **Usage**
1. Ensure all prerequisite libraries are installed.
2. Run the `DNN` script.
3. The pipeline will automatically download the dataset, build the model, train it, and display the final evaluation metrics and plots in the console.
