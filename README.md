This project has been implemented by Gurv Gupta. In this project, I aim to detect fraudulent behavior in bank transactions using machine learning models.
The dataset used for this project is collected from various resources and real-world data which is a simulated dataset created using a sample of transactional data provided by various bank in India (https://www.kaggle.com/datasets/amanindiamuz/financial-dataset-for-fraud-detection-in-a-comapny).

## Folder Structure 
    .
    ├── ipynb-checkpoints                   # Source files (Python scripts and notebooks)
    ├── Data-dictionary                    
    └── README.md

## Source Files

- code/transaction-fraud.ipynb : This script contains the code for data preprocessing, analysing and building fraud detection models using intrinsic features obtained from the dataset.

## Instructions to run the code

All the instructions mentioned below must be run from a terminal session.


To build and test the performance of classifiers using just intrinsic features from the dataset, just load the file in your system, create a jupyter instance and run all the cells in kernel column of notebook or run it cell by cell. 

The dashboard can then be accessed on the browser using this URL - http://localhost:8000/

## Python libraries used
- NumPy - v1.18.1
- Pandas - v0.25.3
- scikit-learn - v0.22.2.post1
