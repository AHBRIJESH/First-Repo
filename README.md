# Naive Bayes Classifier for Exam Score Prediction

This repository contains a simple implementation of a Naive Bayes classifier to predict the probability of a student scoring above 90 in an examination based on various parameters. The classifier utilizes the Naive Bayes algorithm to analyze and make predictions using a dataset with relevant features.

## Features

- **Parameters Used:**
  - Hours of Study
  - Previous Exam Scores
  - Attendance Percentage
  - Mock Test Performance

- **Target Variable:**
  - Probability of Scoring Above 90

## Dataset

The dataset used for training and testing the model is included in the 'data' directory. It comprises a collection of student records with corresponding scores and attributes.

## Implementation

The `naive_bayes_classifier.py` script contains the implementation of the Naive Bayes classifier. It preprocesses the data, trains the model, and provides a function to predict the probability of scoring above 90 for a given set of parameters.

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/naive-bayes-exam-prediction.git
   cd naive-bayes-exam-prediction
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the `naive_bayes_classifier.py` script to train the model and make predictions:

   ```bash
   python naive_bayes_classifier.py
   ```

4. Explore the results and modify the parameters in the script to experiment with different scenarios.

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the functionality or documentation of this project.
