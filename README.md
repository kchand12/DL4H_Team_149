# Team 149-ICU LoS with TPC Model
This project focuses on predicting the length of stay (LoS) in ICU using a deep learning approach with a novel Temporal Pointwise Convolution (TPC) model. The model processes time-series data from Electronic Health Records to help optimize ICU bed management.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine or Google Colab for development and testing purposes.

### Prerequisites
Install all the packages outlined in requirments.txt

Use a python version of 3.6

Complete certification to gain access to eICU database: https://physionet.org/content/eicu-crd/2.0/

### Running the Notebook
Download the ipynb notebook

Replace eICU data paths to your local files

Run all cells

Note: Training does not take place in this file as it was done in an outside enivorment due to cpu constraints.

### References
Most functions and codes were taken from https://github.com/EmmaRocheteau/TPC-LoS-prediction/tree/master to reproduce. Refer to this github if you want to train the model from scratch locally. 
