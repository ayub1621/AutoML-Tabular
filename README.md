# Tabular Classification Model for Pet Adoption Prediction using Vertex AI Python Client Library

This program utilizes the Vertex AI Python client library for the training and deployment of a tabular classification model for online prediction. The program is implemented in Jupyter Lab notebook.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction
Vertex AI is a powerful machine learning platform provided by Google Cloud that enables efficient development, training, and deployment of machine learning models. This program leverages the Vertex AI Python client library to train and deploy a tabular classification model for online prediction.

Tabular classification involves predicting categorical labels based on input features organized in a tabular format. The program demonstrates how to train a tabular classification model using Vertex AI's AutoML capabilities and deploy the trained model to make online predictions.

The program is implemented in Python using the Vertex AI Python client library. Jupyter Lab provides an interactive environment for running and exploring the program.

## Installation
To run this program, you need to have the following dependencies installed:

- Python 3
- Jupyter Lab
- Vertex AI Python client library
- Google Cloud SDK

You can install the Vertex AI Python client library and Google Cloud SDK by following the instructions in the [Vertex AI documentation](https://cloud.google.com/vertex-ai/docs/start/client-libraries).

Once the dependencies are installed, you can clone the repository and navigate to the project directory:

```bash
git clone https://github.com/ayub1621/AutoML-Tabular.git
cd AutoML-Tabular
```

## Usage
1. Launch Jupyter Lab by running the following command in the project directory:
   ```bash
   jupyter lab
   ```

2. In Jupyter Lab, open the `VertexAI-automl-tabular-classification.ipynb` notebook.

3. Follow the instructions in the notebook to set up your Google Cloud project, create a Vertex AI dataset, import data for training, train a tabular classification model, and deploy the model for online prediction.

4. Customize the training configuration, model architecture, and deployment settings based on your requirements. You can experiment with different algorithms, feature engineering techniques, and hyperparameter tuning to improve the classification performance.

5. Run the code cells in the notebook to execute the program, train the tabular classification model, and make online predictions using the deployed model.

## Results
The program aims to train and deploy a tabular classification model using Vertex AI and make online predictions based on the deployed model. The performance of the model depends on factors such as the quality and diversity of the training data, the choice of algorithm, and the effectiveness of the training process.

You can evaluate the performance of the model using classification metrics such as accuracy, precision, recall, or F1 score. Additionally, you may consider monitoring the model's online prediction performance, adjusting deployment resources, or retraining the model periodically to maintain optimal results.
