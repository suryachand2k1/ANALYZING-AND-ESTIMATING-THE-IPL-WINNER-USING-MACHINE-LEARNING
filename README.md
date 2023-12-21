# Cricket Score Prediction

## Project Overview
This Flask-based web application leverages a machine learning model for predicting the first-innings score in cricket matches. It uses historical data to analyze and forecast match outcomes, offering an interactive platform for cricket enthusiasts and analysts.

## Key Features
- **Data-Driven Predictions:** Utilizes a regression model trained on historical cricket match data to forecast first-innings scores.
- **Flask Web Interface:** Provides a user-friendly interface for inputting match parameters and retrieving predictions.
- **Model Serialization:** The machine learning model is serialized using Python's `pickle` module for easy loading and deployment.

## Technical Stack
- **Backend Framework:** Flask, for creating and managing the web server.
- **Data Analysis and Preprocessing:** Conducted in Jupyter Notebooks using Pandas for data manipulation, NumPy for numerical operations, and Matplotlib for data visualization.
- **Machine Learning:** Implementation of a regression algorithm, fine-tuned to predict cricket scores based on various match parameters.
- **Model Deployment:** Deploying the serialized model within the Flask application to process user inputs and generate predictions.

## How to Run Locally
1. Clone the repository to your local machine.
2. Install Python and necessary libraries: `Flask`, `Pandas`, `NumPy`, `Matplotlib`, etc., as listed in `requirements.txt`.
3. Navigate to the project directory and execute `python app.py` to start the Flask server.
4. Open a web browser and enter the local server URL to interact with the application.

## Setting Up the Environment
- Install Python 3.x.
- Use `pip` to install the dependencies: `pip install -r requirements.txt`.
