# Backend Web Development & API Design - Flask API with Prediction

## Overview

This project demonstrates how to set up a **Flask** API that allows for **prediction** using a simple **machine learning model**. The API receives input data, processes it using a trained model, and returns a prediction. The results are also stored in an **SQLite** database for later retrieval.

## Features

- **Flask API**: Provides two endpoints, `/predict` and `/predictions`.
  - `/predict`: Accepts `POST` requests with features, uses the trained model to make predictions, and stores the results in a database.
  - `/predictions`: Accepts `GET` requests to retrieve previously stored predictions from the database.
- **Machine Learning Model**: A simple **Linear Regression** model is used for predictions.
- **SQLite Database**: Predictions are stored in an SQLite database, which can be queried via the API.
- **Docker Support**: Easily deploy the API with Docker.
- **Cloud Deployment**: Guide for deploying the API to AWS Elastic Beanstalk or Google Cloud App Engine.

## Technologies Used

- **Flask**: Web framework to build the API.
- **scikit-learn**: Machine learning library to create and use the prediction model.
- **pandas**: Data manipulation library used for creating and preparing data.
- **SQLite**: Lightweight database to store prediction results.
- **pickle**: Serialization tool to save and load the machine learning model.

## Setup and Installation

### Requirements

- Python 3.7 or higher
- Pip (for installing dependencies)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/flask-api-with-prediction.git
cd flask-api-with-prediction
