# Olympic Medal Success Prediction Using Machine Learning and Deep Learning

## Project Overview

This project investigates the use of traditional machine learning and deep learning models to predict Olympic medal-winning outcomes.

The project supports my broader mission of promoting sports development and improving opportunities for young African athletes.

By analyzing historical Olympic results, this study explores patterns associated with medal-winning outcomes and compares the performance of different classification algorithms.

## Research Question

How effectively can traditional machine learning and deep learning models predict Olympic medal-winning outcomes using athlete characteristics and competition information, and what insights can these findings provide for African sports development?

## Dataset

Dataset: 120 Years of Olympic History

Original Author: Randi Griffin

Source: Historical Olympic records from Sports Reference

Original Samples: 271,116

Original Features/Columns: 15

Target Variable: Medal

Classification Type: Binary Classification

Target Classes:
- 1: Medal
- 0: No Medal

The complete original dataset is available in the shared Google Drive folder.

## Methodology

The project follows these stages:

1. Dataset loading and exploratory data analysis.
2. Data preprocessing and feature engineering.
3. Group-based training, validation, and test splitting.
4. Traditional machine learning model training.
5. Deep learning model training using TensorFlow/Keras and tf.data.
6. Hyperparameter experimentation and TensorBoard logging.
7. Model evaluation and error analysis.

## Models Implemented

### Traditional Machine Learning

- Logistic Regression
- Random Forest
- Linear Support Vector Classifier

### Deep Learning

- Feedforward Neural Networks using Keras Sequential API

## Experiments

Ten experiments were conducted:

- Six traditional machine learning experiments.
- Four deep learning experiments.

The experiments investigated class weighting, regularization, feature engineering, dropout, and neural network architecture.

## Final Test Results

| Metric | Random Forest (ML-06) | Neural Network (DL-02) |
|---|---:|---:|
| Accuracy | 0.7687 | 0.7654 |
| Precision | 0.3482 | 0.3624 |
| Recall | 0.6321 | 0.7545 |
| F1-score | 0.4491 | 0.4896 |
| ROC-AUC | 0.7942 | 0.8449 |
| Average Precision | 0.4965 | 0.5352 |

The deep learning model (DL-02) achieved the highest test F1-score of 0.4896.

However, the traditional machine learning model achieved slightly higher accuracy.

## Project Files

- Olympic_Medal_Prediction_ML_DL.ipynb: Main project notebook.
- README.md: Project documentation.
- requirements.txt: Python dependencies.

The dataset, saved models, experiment results, and TensorBoard logs are stored in Google Drive.

## Reproducibility

To reproduce the project:

1. Download or clone this GitHub repository.
2. Open the notebook in Google Colab.
3. Install the dependencies listed in requirements.txt if needed.
4. Connect Google Drive.
5. Run the notebook cells sequentially.

The notebook contains the dataset loading, preprocessing, model training, experimentation, and evaluation procedures.

Random seeds are used to improve reproducibility.

## Limitations

The dataset contains historical Olympic records from 1896 to 2016.

The classification target is imbalanced, with fewer medal-winning records than non-medal records.

The dataset also lacks information about athlete training quality, financial support, sporting infrastructure, and development opportunities.

Therefore, the models should not be interpreted as direct measures of young athletes' potential.

## Google Drive

The original dataset, trained models, and experiment logs are available through the shared Google Drive folder.

Google Drive Folder: (https://drive.google.com/drive/folders/1ls6JGOkxUGgS3rCfucLx5QCh5H6eg-0o?usp=drive_link)

## Conclusion

The project demonstrates that deep learning can outperform the selected traditional machine learning approaches in predicting Olympic medal-winning outcomes.

The findings also highlight the importance of class imbalance, model optimization, and critical evaluation when applying machine learning to sports data.
