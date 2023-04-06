# PP7: COVID-19 X-Ray Image Classification

This repository contains the implementation of a deep learning model for classifying X-ray images of COVID-19 diagnosed people using the MobileNetV2 model and Keras. The model achieves an accuracy of over 93%.

## Dataset
The dataset used for this project can be found on Kaggle: [COVID-19 Radiography Database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)

## Installation

First, install the required packages:

```bash
!pip install -q kaggle
```

## Usage

1. Upload the `kaggle.json` file containing your Kaggle API key to Google Colab.
2. Run the code blocks in the provided Jupyter Notebook to download and preprocess the dataset.
3. Train the MobileNetV2 model on the preprocessed dataset.
4. Save the trained model and visualize the training and validation loss and accuracy.
5. Perform predictions using the trained model.

## Results
The model achieves an accuracy of over 93% on the test dataset
