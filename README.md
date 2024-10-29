# Artificial Neural Networks for Flower Classifiction and Object Detection

# Code Implementation & Technical Report
## Dataset 1 - Custom Flower Species Dataset

This dataset can be found in Canvas - [Download](https://ufl.instructure.com/files/82943306/download?download_frd=1) the training and test images and labels.

## Dataset 2 -  Car Detection Dataset

This dataset can be found in Canvas - [Download](https://ufl.instructure.com/files/82943015/download?download_frd=1) the training images, test images and the csv bounding box coordinates.

## File structure

This repository contains the following files:   
1. "Artificial Neural Networks - Answers.ipynb"
  - This python notebook file contains all the question statements and answers provided with code implementations and visualizations that were also included in the report.   
2. "Artificial Neural Networks - Answers.pdf"
  - This is a pdf version of the previous file for better readability in GitHub.
3. "training.ipynb"
  - This file contains streamlined code for all the trainings and experimentations done on the training set.
  - This code also saves the trained models in pickle files.
4. "test.ipynb"
  - This python notebook contains the code to test on the test data.
  - To run this file, trained model files are required.
  - If you want to directly test the data, you can download the trained model files submitted in the Canvas 'Project 3' Assignment page - Attempt 2.
  - Alternatively, you can also sownload the requied datasets [here](https://drive.google.com/drive/folders/158okexVLjYbxupI6fsZaLHw9UMkdwtzM?usp=sharing).
5. "Report.pdf"
  - The 4-page IEEE Report in the PDF format for this project.


## How to use the code

1. Have the datasets in the same place as you have the training.ipynb and test.ipynb files.
2. Run all the cells in training.ipynb. This will train the models on the training data and create trained model files as pickle (.pkl) files in the same file location. (Make sure to `pip install ultralytics` to run the YOLOv8 model.)   
3. Make sure that all the model files are present in the same location as the training and testing files and run all the cells in the test.ipynb to test the models.


## Author
Akash Kumar Kondaparthi