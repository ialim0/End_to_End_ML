# Pricing Prediction

This project aims to predict house prices using machine learning techniques. The project provides an end-to-end solution for predicting house prices based on various features using a linear regression model.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The project consists of the following components:

- **Linear Regression Model Implementation (`Linear Regression ML Implementation.ipynb`)**: This Jupyter Notebook contains the implementation of the linear regression model used for predicting house prices. It covers data preprocessing, model training, and evaluation.

- **Dockerfile**: Dockerfile for containerizing the application.

- **app.py**: Flask application for serving the machine learning model as a REST API.

- **regmodel.pkl**: Pickled file containing the trained linear regression model.

- **scaling.pkl**: Pickled file containing the scaler used for feature scaling.

- **templates/home.html**: HTML template for the web application frontend.

## Installation

To install and run this project locally, follow these steps:

1. Clone this repository.
git clone https://github.com/ialim0/pricing_prediction.git

2. Navigate to the project directory.

cd pricing_prediction


3. Install the required dependencies.
pip install -r requirements.txt


## Usage

1. Run the Flask application.
python app.py


2. Open your web browser and go to [http://localhost:5000](http://localhost:5000) to access the web interface for house price prediction.

3. Enter the required features for the house in the provided form and click on the "Predict" button to get the predicted house price.

Alternatively, you can use the provided REST API endpoint for predictions.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork this repository.

2. Create a new branch.
git checkout -b feature/new-feature

3. Make your changes and commit them.
git commit -m "Add new feature"

4. Push to the branch.
git push origin feature/new-feature


5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


