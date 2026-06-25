# Dataset

The dataset is not included in this repository because it is large.

This project uses the Breast Cancer Histopathology dataset from Kaggle, based on the BreaKHis dataset.

## Dataset Source

Kaggle dataset:

https://www.kaggle.com/datasets/anaselmasry/breast-cancer-dataset?select=BreaKHis_Total_dataset

Research paper:

https://pubmed.ncbi.nlm.nih.gov/26540668/

## Dataset Description

The dataset contains histopathological breast cancer images classified into two classes:

- Benign
- Malignant

The Kaggle version used in this project contains approximately 7,783 images:

- 2,479 benign images
- 5,304 malignant images

The task is binary image classification, where the model predicts whether a histopathology image is benign or malignant.

## Expected Local Structure

```text
dataset/
└── BreaKHis_Total_dataset/
    ├── benign/
    └── malignant/
