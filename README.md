# NYC Taxi Trip Duration Prediction | MLOps

## Project Overview

This project focuses on predicting the duration of taxi trips in New York City using machine learning operations (MLOps) practices. It involves setting up a structured GitHub repository, developing a prediction model, integrating MLflow for experiment tracking, using DVC for data version control, and deploying a real-time prediction web application. The solution includes automated CI/CD pipelines for testing, building, and deploying the model on scalable AWS infrastructure.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Project Description

The NYC Taxi Trip Duration Prediction project involves developing and deploying a machine learning model to predict taxi trip durations. The project incorporates MLOps practices, including version control, experiment tracking, and deployment automation. The end solution is a real-time prediction web application deployed on AWS.

## Features

- **GitHub Repository & Development:** Set up a well-structured GitHub repository with project templates, managed dependencies, and implemented logging and utility modules.
- **Model Development:** Developed a taxi trip duration prediction model using XGBoost, transitioning from notebook experiments to modular Python scripts.
- **MLflow Integration:** Utilized MLflow for experiment tracking, model versioning, and registration to manage and monitor model performance.
- **DVC for Pipeline Management:** Applied Data Version Control (DVC) for data versioning, pipeline management, and ensuring reproducibility of data processing and feature engineering.
- **Prediction Pipeline & Flask Application:** Designed a prediction pipeline and developed a Flask-based web application for real-time predictions, containerized using Docker.
- **CI/CD Pipelines:** Implemented CI/CD pipelines using GitHub Actions for automated testing, building, and deployment.
- **AWS Deployment:** Deployed the application on AWS using ECS/EKS for scalable infrastructure.

## Technologies Used

- **Machine Learning:** XGBoost
- **Experiment Tracking:** MLflow
- **Data Version Control:** DVC
- **Web Framework:** Flask
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Cloud Infrastructure:** AWS ECS/EKS
- **Programming Language:** Python

## Methodology

### GitHub Repository & Development

- **Setup:** Established a GitHub repository with a structured project template, managed dependencies, and implemented logging and utility modules.

### Model Development

- **Prediction Model:** Developed a taxi trip duration prediction model using XGBoost, evolving from Jupyter notebook experiments to modular Python scripts.

### MLflow Integration

- **Experiment Tracking:** Used MLflow to track experiments, manage model versions, and register models for performance monitoring.

### DVC for Pipeline Management

- **Data Versioning:** Managed data versions and pipeline stages using DVC to ensure reproducibility and effective feature engineering.

### Prediction Pipeline & Flask Application

- **Pipeline Design:** Created a prediction pipeline for the model and developed a Flask-based web application for real-time predictions.
- **Containerization:** Containerized the application using Docker to ensure consistent deployment across environments.

### CI/CD Pipelines

- **Automation:** Implemented CI/CD pipelines with GitHub Actions to automate testing, building, and deployment processes.

### AWS Deployment

- **Scalability:** Deployed the application on AWS using ECS/EKS to ensure scalable and reliable infrastructure.

## Results

- **Model Performance:** Achieved robust prediction accuracy for taxi trip durations using XGBoost.
- **Real-Time Predictions:** Enabled real-time predictions via the Flask web application.
- **Scalable Deployment:** Ensured scalable and reliable deployment on AWS ECS/EKS.

## Usage

1. **Setup Repository:** Clone the GitHub repository and set up your development environment.
2. **Data Preparation:** Use DVC to manage data versions and prepare data for training.
3. **Model Training:** Train the XGBoost model using the provided scripts.
4. **Experiment Tracking:** Track experiments and manage models using MLflow.
5. **Flask Application:** Run the Flask application locally or deploy it using Docker.
6. **CI/CD:** Use GitHub Actions to automate testing, building, and deployment.
7. **Deployment:** Deploy the application on AWS ECS/EKS for scalable infrastructure.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. For more details, see the [CONTRIBUTING](CONTRIBUTING.md) guidelines.
