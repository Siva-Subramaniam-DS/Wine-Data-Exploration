# Wine_dataset

1. Imports and Setup
Libraries: Import necessary libraries for data manipulation (pandas, numpy), visualization (matplotlib, seaborn), and machine learning (sklearn, tensorflow).

2. Set Kaggle Credentials and Download Data
Credentials: Set Kaggle API credentials to access the dataset.
Download and Unzip: Download and unzip the dataset file from Kaggle.

3. Load and Inspect Data
Load Data: Read the CSV file into a DataFrame.
Inspect Data: Check the shape (dimensions) of the DataFrame, view the first few rows, and check for missing values.

4. Prepare Data for Training
Split Data: Separate features (X) and labels (y).
Train-Test Split: Split data into training and testing sets (80% training, 20% testing).

5. Define and Compile the Model
Model Definition: Create a Sequential model with three hidden layers (using ReLU activation) and one output layer (using linear activation for regression).
Compile Model: Use mean squared error as the loss function and Adam optimizer. Track mean absolute error as a metric.

6. Train the Model
Training: Train the model with training data for 100 epochs and a batch size of 10. Validate the model on the test set during training.

8. Plot Training and Validation Metrics
Plot Metrics: Visualize the training and validation mean absolute error and loss over epochs to evaluate model performance.

10. Evaluate the Model
Evaluation: Test the model on the test set to get the final loss and mean absolute error.

12. Simple TensorFlow Model for Illustration
Define a Simple Model: Create a minimalistic TensorFlow model with one dense layer.
Compile and Train: Train it on sample data (xs and ys) and then make a prediction.

Summary
*   Data Preparation: Load, clean, and split the data.
*   Model Building: Define and compile a neural network model.
*   Training and Evaluation: Train the model, plot performance metrics, and
    evaluate it.
*   Inference: Use the model to predict new data.
