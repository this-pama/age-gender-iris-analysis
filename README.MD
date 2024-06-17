# Age-Gender Iris Analysis

This repository contains a Jupyter notebook for analyzing iris images to predict age and gender using a machine learning model. The notebook utilizes TensorFlow and Keras libraries for model creation and training.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to predict the age and gender of individuals based on iris images. The analysis uses a deep learning approach to train a model on a dataset of iris images categorized by age groups and gender.

## Installation
To run this project, ensure you have the following libraries installed:

```bash
pip install numpy opencv-python tensorflow scikit-learn
```

## Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com/this-pama/age-gender-iris-analysis.git
   cd age-gender-iris-analysis
   ```

2. **Open the Jupyter notebook:**
   Ensure you have Jupyter installed. You can open the notebook using the following command:
   ```bash
   jupyter notebook inits.ipynb
   ```

3. **Run the notebook:**
   Follow the steps in the notebook to mount Google Drive, load the dataset, preprocess the data, train the model, and evaluate the results.

## Dataset
The dataset used for this project is stored in Google Drive and contains iris images categorized into different age groups and genders. The folder contains the GMBAMU-IRIS dataset. The notebook mounts Google Drive to access the dataset.

## Model Architecture
The model is built using TensorFlow and Keras. It consists of multiple convolutional layers for feature extraction, followed by fully connected layers for classification.

## Training
The notebook splits the dataset into training and testing sets. It then trains the model using the training set and evaluates it on the testing set. The training process includes loading images, preprocessing, and model training.

## Results
After training, the model's performance is evaluated based on accuracy metrics. The results are displayed within the notebook.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.
