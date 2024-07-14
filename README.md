# Vehicle Movement Analysis and Insight Generation

## Overview

This project aims to analyze vehicle movements and generate insights within a college campus. 
The system detects vehicles, captures entry and exit times, and recognizes license plates. 
It matches license plates against a database to identify authorized and unauthorized vehicles.
The project provides visual insights, including occupancy trends, peak times enhancing campus security and vehicle management.


This repository contains a dataset aimed at developing algorithms for license plate detection and character recognition tasks. The dataset is structured into training and test sets, designed to facilitate the training and evaluation of models for automatic license plate recognition (ALPR) systems.

## Dataset Overview

### Training Set 1
- **Description**: 900 vehicle images with annotated bounding boxes around license plates.
- **Usage**: Primarily used for training models to detect the presence and location of license plates on vehicles.

### Training Set 2
- **Description**: 900 isolated license plate images with annotated alphanumeric characters.
- **Usage**: Used for training models to recognize and extract alphanumeric characters from license plates.

### Test Set
- **Description**: 201 images for evaluating both license plate detection and character recognition.
- **Usage**: Provides a benchmark for evaluating the performance of trained models in detecting license plates and recognizing characters.

## Applications
- **License Plate Detection**: Develop algorithms to detect license plates on vehicles.
- **Character Recognition**: Train models to extract alphanumeric characters from license plates.
- **Evaluation**: Use the test set to measure and compare the accuracy of different algorithms.

## Access
You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection?resource=download).

## License
This dataset is provided under the terms specified by Kaggle. Refer to the Kaggle dataset page for more details.

# Models Used

This repository implements a series of steps using various tools and techniques for vehicle detection, license plate recognition, and generating insights from movement and parking data.

## Step 1: Load the Dataset
- **Tools**: Python, OpenCV
- **Description**: Load the dataset containing vehicle images and license plate annotations.

## Step 2: Data Preprocessing
- **Tools**: OpenCV, Pandas, NumPy
- **Description**: Prepare the dataset for analysis by cleaning and transforming data as necessary.

## Step 3: Exploratory Data Analysis (EDA)
- **Tools**: Matplotlib, Seaborn
- **Techniques**: Visualize vehicle entry/exit times, occupancy trends to understand patterns in parking lot usage.

## Step 4: Vehicle Matching
- **Tools**: OpenCV, Tesseract OCR
- **Techniques**: Perform license plate recognition and match recognized plates to a database of vehicles.

## Step 5: Insight Generation
- **Tools**: Pandas, Matplotlib
- **Techniques**: Generate insights from movement patterns and parking data to understand peak occupancy and trends.

## Step 6: Implementing the Solution in a Scalable Manner
- **Tools**: TensorFlow Lite, OpenVINO
- **Techniques**: Deploy AI models on Edge devices to ensure scalability and efficiency in real-world applications.

## Step 7: Creating a User-friendly Interface
- **Tools**: Flask, HTML, CSS
- **Techniques**: Develop a web interface to display insights and visualizations, making the data accessible and actionable.

---

This structure provides a clear overview of the steps involved in your project, the tools used for each step, and the techniques applied to achieve specific goals related to vehicle detection, license plate recognition, and generating insights from data. Adjust the descriptions and tools as per your specific implementation and project details.




