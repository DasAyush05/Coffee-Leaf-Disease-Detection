# Coffee Leaf Disease Classification

An AI/ML research project exploring the classification of coffee leaf diseases using deep learning-based feature extraction and machine learning.

## Overview

Coffee plants can be affected by several leaf diseases that impact plant health and crop productivity. Identifying these diseases from leaf images can support early detection and informed agricultural decision-making.

This project explores a classification pipeline combining deep learning feature extraction with a machine learning classifier to distinguish between healthy coffee leaves and different disease categories.

## Project Architecture

The proposed architecture combines features extracted using MobileNetV2 and DenseNet201, followed by feature concatenation and Support Vector Machine (SVM) classification.

**Pipeline:**

Coffee Leaf Images → Feature Extraction → Feature Concatenation → SVM Classification → Predicted Class

## Disease Classes

The proposed classification categories are:

- Healthy
- Miner
- Rust
- Phoma
- Cercospora

## Technologies and Methods

- Python
- Deep Learning
- MobileNetV2
- DenseNet201
- Feature Extraction and Feature Concatenation
- Support Vector Machine (SVM)
- Image Classification

## Project Structure

The repository will be organized as follows:

```text
coffee-leaf-disease-classification/
├── README.md
├── notebooks/
├── src/
├── data/
├── results/
├── docs/
└── requirements.txt
```

- `notebooks/` — experimentation and model development notebooks.
- `src/` — reusable source code for preprocessing, feature extraction, and classification.
- `data/` — dataset instructions or metadata; large datasets should be downloaded separately.
- `results/` — evaluation outputs, plots, and confusion matrices.
- `docs/` — project documentation and architecture diagrams.
- `requirements.txt` — Python dependencies.

## Current Status

Repository setup and project documentation are in progress. The implementation, experiments, and evaluation results will be documented as the project develops.

## Research and Evaluation

The implementation should be evaluated using appropriate classification metrics, such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

Results should be added after running the experiments and verifying the outputs.

## Dataset

Dataset details, source, usage conditions, and download instructions will be documented here once the dataset used for the project is confirmed.

## How to Run

Setup instructions will be added after the implementation and dependency list are finalized.

## Author

**Ayush Das**

Computer Science Engineering | Artificial Intelligence and Machine Learning

- GitHub: https://github.com/DasAyush05
- LinkedIn: https://www.linkedin.com/in/ayush-das-65b533289/

## Disclaimer

This repository documents an AI/ML project exploring coffee leaf disease classification. Predictions from image classification models should not be treated as a substitute for expert agricultural diagnosis.
