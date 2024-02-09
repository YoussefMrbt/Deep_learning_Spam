
# Spam Message Detection with Deep Learning

This project focuses on developing an automated spam detection system using deep learning techniques. Aimed at enhancing user experience and security for AT&T's mobile services, this initiative leverages a labeled dataset to identify and flag spam SMS messages. By applying simple to advanced models, including regularization methods like Lasso and Ridge, this project seeks to create a robust classifier capable of distinguishing between spam and legitimate ("ham") messages.

## Project Structure

spam-detection-deep-learning/
│
├── datasets/
│   └── spam.csv            # Dataset containing labeled messages
│
└── AT&T_spam_detector.ipynb    # Jupyter notebook with preprocessing and model training

## Dataset Overview

The spam.csv file within the datasets folder forms the core of our analysis. This CSV file comprises SMS messages that have been labeled as 'spam' or 'ham', providing a basis for training and evaluating our deep learning models.

## Notebook Details

The Spam_Detection.ipynb notebook contains the complete workflow for this project, divided into several key sections:

- Data Preprocessing: Initial analysis and preparation of the SMS data for modeling, including cleaning and text normalization.
- Model Development: Implementation of deep learning models starting from basic architectures. The notebook progresses to models incorporating L1 (Lasso) and L2 (Ridge) regularization techniques to enhance performance and minimize overfitting.
- Evaluation: Comparison of model performances based on accuracy, precision, recall, and F1 score, among other relevant metrics, to identify the most effective approach for spam detection.

## Goals

- To automate the detection of spam messages using deep learning, reducing the reliance on manual flagging.
- To explore the impact of regularization techniques on the performance of spam detection models.
