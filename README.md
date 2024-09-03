----------Perceptron Classification Project-----------------
This project demonstrates the implementation of a perceptron algorithm to classify gender based on height and weight data. The project includes tasks such as reading the dataset, performing train-test splits, training the algorithm, and visualizing the results.
------------------------------------------------------------
Table of Contents
Overview
Dataset
Tasks
Usage
Results
Contributing
License

---------------------------------------------Overview-----------------------------------------------------------------
This project is part of the learning activities for understanding the basics of artificial neurons and neural networks. 
The goal is to classify gender based on height and weight data using a simple perceptron algorithm.
The project includes the following steps:
Reading the data from a CSV file.
Performing a train-test split on the dataset.
Training the perceptron model.
Visualizing the data and the decision boundary.

Dataset
The dataset used in this project consists of height, weight, and gender data. The CSV file 01_heights_weights_sex.csv is loaded and processed to convert the labels into integers for model training.

Tasks
Task 1 - Reading the Data
The dataset is read using pandas, and the features (height and weight) and labels (gender) are extracted. The labels are converted to integers (-1 for female and 1 for male) to match the perceptron class.

Task 2 - Train/Test Split
The dataset is split into training and testing sets using scikit-learn's train_test_split function. A random state is set for reproducibility.

Task 3 - Training the Algorithm
The perceptron algorithm is trained on the training set, and the model's performance is evaluated on the test set. The model's decision boundary is visualized using a scatter plot.

Task 4 - Visualization
The results of the training are visualized, including a plot of misclassification over iterations and a scatter plot of the decision boundary.

Usage
To run the project:
Clone the repository.
Ensure you have the required libraries installed (pandas, numpy, matplotlib, scikit-learn).
Execute the notebook to see the model training and visualization steps.
bash

Copy code
git clone https://github.com/yourusername/perceptron-classification.git
cd perceptron-classification
pip install -r requirements.txt
Open the notebook file in Jupyter and run the cells.

-----------------------Results------------------------------------------------------
The perceptron model achieved a training accuracy of 86.1% and a test accuracy of 85.5%.
The misclassification error decreased significantly over the iterations.
