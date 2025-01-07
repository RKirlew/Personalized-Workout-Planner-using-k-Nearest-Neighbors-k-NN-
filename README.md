# Personalized-Workout-Planner-using-k-Nearest-Neighbors-k-NN-
This project focuses on creating a personalized workout planner using machine learning, specifically the k-Nearest Neighbors (k-NN) algorithm. The goal is to recommend tailored workout routines based on user input such as age, fitness level, fitness goals, and preferred workout types

## Key Features

- **Dataset Creation**: Synthetic dataset generated containing features like age, fitness level, goals, and workout types along with corresponding workout recommendations.
- **Data Preprocessing**: One-hot encoding and normalization of categorical and numerical features to ensure model compatibility.
- **Machine Learning Model**: k-Nearest Neighbors (k-NN) classifier trained on the processed data to predict personalized workout recommendations.
- **Prediction**: Ability to input a new user's preferences and predict suitable workout routines.

## Dataset

- The dataset consists of various user profiles with information on age, fitness level, fitness goals, workout types, and recommended workouts.
- The dataset can be found in the file `expanded_workout_data.csv`.

## Model Training

- The k-NN model was trained using the processed dataset, achieving an optimal number of neighbors (k=5) for accurate predictions.
- The dataset was split into training and testing sets to evaluate model performance.

## Usage

### Data Preparation:

- The dataset can be created or modified using synthetic data generation techniques.
- Ensure that the input features match the training data format for accurate predictions.

### Model Training:

- Utilize the k-NN model to train on the dataset, making sure to apply proper data preprocessing steps.

### Prediction:

- Input a new user’s details (age, fitness level, goals, workout type), ensuring the features align with the trained model.
- Obtain personalized workout recommendations based on the trained model’s predictions.
