
# Vodafone Customer Churn Prediction App

## Overview

The Vodafone Customer Churn Prediction App is a machine learning-powered web application designed to predict whether a customer is likely to churn, based on historical data. The app is built using Python and Streamlit, providing an interactive and user-friendly interface for real-time predictions. This tool is particularly valuable for telecom companies looking to enhance customer retention strategies by identifying at-risk customers and taking proactive measures.

## Features

- **Interactive User Interface**: A simple, clean UI where users can input customer data and receive instant churn predictions.
- **Real-Time Predictions**: Input customer details and get immediate feedback on whether the customer is likely to churn.
- **Data Visualization**: Visual insights into customer data, including feature importance and data distribution.
- **Model Explanation**: Understand the factors driving churn predictions with built-in model interpretability features.
- **Deployable with Docker**: The app is containerized using Docker for easy deployment across various environments.

## Project Structure

- **data/**: Contains the historical customer data used for model training.
- **modules/**: Python scripts for data processing, feature engineering, and model training.
- **app.py**: The main Streamlit script that runs the application.
- **Dockerfile**: Configuration file for containerizing the application.
- **docker-compose.yml**: Configuration file for Docker Compose to manage multi-container applications.
- **README.md**: This documentation file.
- **requirements.txt**: Lists all Python dependencies required to run the application.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- **Python 3.7+**
- **pip** (Python package installer)
- **Docker**
- **Docker Compose**

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/kbay9/P4-Embedding-Machine-Learning-Models-in-GUIs.git
    cd vodafone-churn-prediction-app
    ```

2. **Install the required Python packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

    The app will start on `http://localhost:8501`.

### Using Docker and Docker Compose

1. **Install Docker Compose**:
    - Make sure Docker is installed and then install Docker Compose. Refer to the [official Docker Compose installation guide](https://docs.docker.com/compose/install/) if you haven't done so already.

2. **Build the Docker Compose environment**:
    ```bash
    docker-compose build
    ```

3. **Run the Docker Compose environment**:
    ```bash
    docker-compose up
    ```

    The app will be accessible at `http://localhost:8501`.

## Usage

- **Input Data**: Enter customer information (e.g., gender, senior citizen status, tenure, etc.) into the app’s fields.
- **Predict Churn**: Click on the "Predict Churn" button to receive a prediction on whether the customer is likely to churn.
- **Explore Visualizations**: Use the app’s built-in data visualization tools to understand the factors influencing churn.

## Deployment

To deploy the app for production use, consider using cloud services like AWS, GCP, or Heroku, or deploying via Docker on your server.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or find any bugs, please create an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Vodafone** for providing the customer data used in this project.
- **Streamlit** for creating an amazing platform for developing and deploying machine learning web apps.
- **Azubi Africa** for their invaluable resources and training that contributed to the success of this project.
