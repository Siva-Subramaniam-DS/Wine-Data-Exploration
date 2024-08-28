# Wine Dataset 🍷

## Table of Contents 📍
- [Imports and Setup](#imports-and-setup)
- [Set Kaggle Credentials and Download Data](#set-kaggle-credentials-and-download-data)
- [Load and Inspect Data](#load-and-inspect-data)
- [Prepare Data for Training](#prepare-data-for-training)
- [Define and Compile the Model](#define-and-compile-the-model)
- [Train the Model](#train-the-model)
- [Plot Training and Validation Metrics](#plot-training-and-validation-metrics)
- [Evaluate the Model](#evaluate-the-model)
- [Simple TensorFlow Model for Illustration](#simple-tensorflow-model-for-illustration)
- [Summary](#summary)

## `Imports and Setup`
- **Libraries:** Import necessary libraries for data manipulation (`pandas`, `numpy`), visualization (`matplotlib`, `seaborn`), and machine learning (`sklearn`, `tensorflow`).

## `Set Kaggle Credentials and Download Data`
- **Credentials:** Set Kaggle API credentials to access the dataset.
- **Download and Unzip:** Download and unzip the dataset file from Kaggle.

## `Load and Inspect Data`
- **Load Data:** Read the CSV file into a DataFrame.
- **Inspect Data:** Check the shape (dimensions) of the DataFrame, view the first few rows, and check for missing values.

## `Prepare Data for Training`
- **Split Data:** Separate features (X) and labels (y).
- **Train-Test Split:** Split data into training and testing sets (80% training, 20% testing).

## `Define and Compile the Model`
- **Model Definition:** Create a Sequential model with three hidden layers (using ReLU activation) and one output layer (using linear activation for regression).
- **Compile Model:** Use mean squared error as the loss function and Adam optimizer. Track mean absolute error as a metric.

## `Train the Model`
- **Training:** Train the model with training data for 100 epochs and a batch size of 10. Validate the model on the test set during training.

## `Plot Training and Validation Metrics`
- **Plot Metrics:** Visualize the training and validation mean absolute error and loss over epochs to evaluate model performance.

## `Evaluate the Model`
- **Evaluation:** Test the model on the test set to get the final loss and mean absolute error.

## `Simple TensorFlow Model for Illustration`
- **Define a Simple Model:** Create a minimalistic TensorFlow model with one dense layer.
- **Compile and Train:** Train it on sample data (`xs` and `ys`) and then make a prediction.

## `Images 📷`
![1](https://github.com/user-attachments/assets/65ef0264-19fd-4d5b-8e77-77644e732113)
![2](https://github.com/user-attachments/assets/9b794f30-1640-4d60-8616-f073b3cfac4f)
![3](https://github.com/user-attachments/assets/84257db4-3f02-4566-bd83-22b07a292e93)
![4](https://github.com/user-attachments/assets/c65e003a-60d3-4821-a8f7-8730fc04851d)
![5](https://github.com/user-attachments/assets/7fd873f8-8cfd-40ac-9e8c-cd582a053efa)
![6](https://github.com/user-attachments/assets/60c5c798-239b-4c47-ad23-323cf383a1d0)
![7](https://github.com/user-attachments/assets/776deb32-690a-4239-8346-f73be53c1c74)
![8](https://github.com/user-attachments/assets/82d4b1d7-3353-4407-8ee9-b09d698dda61)
![9](https://github.com/user-attachments/assets/ec3ab7ec-004e-4aee-a46e-b389deb32399)

## `Summary`
- **Data Preparation:** Load, clean, and split the data.
- **Model Building:** Define and compile a neural network model.
- **Training and Evaluation:** Train the model, plot performance metrics, and evaluate it.
- **Inference:** Use the model to predict new data.
