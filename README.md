# README

## ML-C-CARS ( Machine Learning Classification with Car images)

This little project was done to practice and showcase the machine learning techniques for classification problems.


**Author:** Mike Avens

**Last updated:** May 20 2023

## Table of Contents

1. [Introduction](#introduction)
2. [Notebook Overview](#notebook-overview)
3. [How to Run](#how-to-run)
4. [Dependencies](#dependencies)
5. [License](#license)
6. [Acknowledgements](#acknowledgements)

---

## Introduction

This Jupyter notebook is based on [Kaggle data cars data](https://www.kaggle.com/datasets/prondeau/the-car-connection-picture-dataset). 
Two questions that are feasible to answer with the current dataset:
1. Is it possible to identify car brands based on the image?
2. Is it possible to identify the year a car was made based on the image?

I am personally a car geek, so doing this project was a lot of fun for me!

## Notebook Overview

The notebook contains quick, limited explanations of each block of code. The data is partially showcased and the overall feature vector shape and dimensionality is apparent.
The data contains 64,464 images of cars scraped from the internet. Some of those images are repetitive or miss-labeled. This issue is also showcased and discussed within the notebook.

## Techniques used:

Feature Extraction:
  1. HOG (Histogram of gradients)
     
Classification:
  1. Support Vector Machine (SVM)
  2. Random Forest (RFC)
  3. T-SNE (In the workings)

Data Visualisation:
  1. Confusion matrix 
  2. Heatmaps
  3. Plots

     
## How to Run

1. Clone this repository to your local machine.
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/prondeau/the-car-connection-picture-dataset)
3. Install the required libraries using `pip install -r requirements.txt` and Jupyter Notebook.
4. Launch Jupyter Notebook: `jupyter notebook` or `python3 -m notebook`.
5. Open the notebook file: `ML-C-CARS.ipynb`.
6. Execute the cells in order.

## Dependencies
- Python 3.9
- Numpy 1.19.5
- Pandas 1.1.5
- Matplotlib 3.3.4
- Scikit-image 0.18.3
- Scikit-learn 0.24.2
- Seaborn 0.11.2


## License

This Jupyter Notebook is licensed under the [MIT License](LICENSE).

## Acknowledgements

Thank you [Paul](https://www.kaggle.com/prondeau) for providing a great dataset!

---
